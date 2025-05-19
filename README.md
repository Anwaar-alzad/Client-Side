# Simple Navbar Using `inline-block` in CSS

This project demonstrates how to build a **basic horizontal navigation bar** using the `display: inline-block` property in CSS.

---

## 🔧 How It Works

The key to creating a simple horizontal navbar using `inline-block` is:
- Setting each `<li>` (list item) to `display: inline-block;`
- Removing the default list styling
- Optionally adjusting padding/margins and link styles

---

## 🧱 Example Structure

### 📄 HTML

```html
<div class="nav inline">
        <div class="logo inline">
            <span class="flower">🪷</span>
            <span class="name">Bloom</span>
        </div>
        <div class="nav-menu inline">
            <ul>
                <li class="inline"><a href="#">Home</a></li>
                <li class="inline"><a href="#">About</a></li>
                <li class="inline"><a href="#">Services</a></li>
                <li class="inline"><a href="#">Contact Us</a></li>
            </ul>
        </div>
    </div>
