# Back To Top Button - WordPress Plugin

<img width="1435" height="794" alt="Screenshot 2025-09-05 at 15 35 22" src="https://github.com/user-attachments/assets/5f3599c3-676d-4f25-879b-3104313ff0a8" />



A lightweight WordPress plugin that adds a **Back to Top** button to your website.  
The button smoothly scrolls users back to the top of the page, improving navigation and user experience.

---

## Features
- Clean, lightweight, and easy to install
- Smooth scroll animation
- Appears after scrolling down
- Modern design with hover effect
- Fully responsive
- Works with any WordPress theme

---

## Installation

1. Download the plugin files and create a folder named `back-to-top-button`.
2. Inside the folder, add the following:
   - `back-to-top-button.php` (main plugin file)
   - `css/btt-style.css`
   - `js/btt-script.js`
3. Compress the folder into a `.zip` file.
4. In your WordPress dashboard:
   - Navigate to **Plugins → Add New → Upload Plugin**
   - Upload the `.zip` file
   - Click **Install Now** and then **Activate**

---

## ⚡ Usage
Once activated, the plugin automatically:
- Adds a **Back to Top** button to the bottom-right corner of your site.
- The button appears when scrolling down `300px` and smoothly scrolls to the top when clicked.

No extra configuration is required.

---

## 🛠️ Customization
You can customize the button via `css/btt-style.css`:
- **Color** → Change the `background` property
- **Size** → Adjust `font-size`, `padding`, and `border-radius`
- **Position** → Update `bottom` and `right` values

Example:
```css
.back-to-top {
  background: #ff6600; /* Custom color */
  bottom: 50px;        /* Higher position */
  right: 50px;         /* More space from right */
}
