# Sneaker Product Page – HTML & CSS Properties Documentation

This document explains **the main HTML tags and CSS properties** used in the Sneaker Drops project and specifies **what each property is used for on this page**. It is concise and suitable for **presentation, viva, or exam writing**.

---

## 1. IMPORTANT HTML TAGS USED

* `<div>` – Container for grouping elements and creating layout sections (used in container, product cards, image grids, and size selections).
* `<h1>`, `<h2>` – Headings for page title and product names.
* `<p>` – Taglines or short descriptions for products.
* `<img>` – Displays product images within the image grid.
* `<span>` – Badges (NEW/LIMITED) and size labels.
* `<button>` – Add to Cart call-to-action.
* `<link>` – Connects external CSS and Google Fonts.

---

## 2. IMPORTANT CSS PROPERTIES USED AND THEIR PURPOSE

* `display: flex` – Used to align product cards, center elements, and align sizes horizontally.
* `display: grid` – Creates the 3-column image grid layout for product images.
* `justify-content` & `align-items` – Centers product cards and content within them.
* `background: linear-gradient()` – Adds colorful gradients to body background, product cards, and buttons.
* `border-radius` – Rounds corners of product cards, images, and buttons for a modern look.
* `box-shadow` – Creates neon glow effect on product cards and highlights selected size.
* `position: relative / absolute` – Positions badges correctly on product cards.
* `@keyframes` + `animation` – Animates neon glow effect continuously on product cards.
* `transition` – Smooth hover effects for buttons and sizes.
* `transform: scale()` – Zoom-in effect when hovering on buttons.
* `gap` – Spacing between images in the grid and sizes in the size selector.
* `min-height: 100vh` – Ensures page covers the full viewport height.

---

## 3. SECTIONS OF THIS PAGE

1. **Page Background** – Uses gradient background to cover full screen height.
2. **Page Title** – Centered main heading using text-align and font size.
3. **Container** – Flexbox container holding all product cards.
4. **Product Cards** – Each card uses gradients, border-radius, box-shadow, and animation.
5. **Badges** – Positioned absolutely with background color and font weight.
6. **Image Section** – Grid layout of images with gap and border-radius.
7. **Size Selection** – Flex layout with spacing and hover effects using transition and box-shadow.
8. **Price Display** – Bold and larger font for product price.
9. **Button Section** – Gradient background, rounded corners, hover zoom effect using transform and transition.

---

###
