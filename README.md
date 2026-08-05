# YouTube UI Clone (HTML & CSS)

A pixel-perfect, static frontend clone of the YouTube user interface built using semantic HTML5 and modern CSS techniques (Flexbox and CSS Grid).

---

## 🚀 Live Demo

[View Live Project](https://SeelamPoornica.github.io/Youtube-Clone)

---

## ✨ Key Features & Implementation Details

* **Fixed Header Bar:** Custom navigation bar with search bar layout, voice search button, notification badge counter, and action tooltips on hover[cite: 1, 2].
* **Collapsible Sidebar:** Navigation panel featuring standard YouTube navigation options like Home, Explore, Subscriptions, Library, and YouTube Music[cite: 1, 2].
* **Responsive Video Grid:** CSS Grid layout featuring a dynamic grid that adjusts column counts seamlessly across screens (`1fr` multi-column layouts with custom breakpoints)[cite: 2].
* **Video Cards:** Custom-styled video previews with thumbnail images, channel avatars, title styling, author info, and view count metadata[cite: 1, 2].
* **Interactive Tooltips:** CSS-driven dynamic hover tooltips on standard header buttons[cite: 1, 2].

---

## 🛠️ Tech Stack & Concepts Applied

* **HTML5:** Semantic structural tags (`<header>`, `<nav>`, `<main>`, `<section>`)[cite: 1].
* **CSS3:**
  * **Flexbox:** Used for alignment in header sections and vertical sidebar content[cite: 2].
  * **CSS Grid:** Implemented for layout responsiveness in video card displays and channel metadata grids[cite: 2].
  * **Media Queries:** Added breakpoints (`@media`) to handle multi-column layouts across mobile, tablet, and desktop viewports[cite: 2].
  * **Positioning:** Fixed positioning (`position: fixed`) for continuous navigation header and sidebar accessibility[cite: 2].
* **Google Fonts:** Integrated Google's Roboto font for typography matching YouTube's design guidelines[cite: 1, 2].

---

## 📁 Repository Folder Structure

```text
├── index.html          # Main HTML document
├── youtube.css         # Main stylesheet containing Flexbox & Grid CSS
├── navImg/             # Header icons (Search, Microphone, Upload, Notifications)
├── sidebar/            # Sidebar navigation icons
├── thumbnail/          # Video preview thumbnail images
└── channelPics/        # Channel creator avatar images
