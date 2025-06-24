# jQuery Dimensions Visual Demo

This project demonstrates the use of jQuery's dimension methods with a visual representation of:

- `.width()`
- `.height()`
- `.innerWidth()`
- `.innerHeight()`
- `.outerWidth()`
- `.outerHeight()`

It helps clearly understand what part of a box each method actually measures (content, padding, border).

---

## 📦 Description

The webpage includes:
- A **visually styled box** with color-coded layers:
  - White for **content**
  - Light blue for **padding**
  - Blue for **border**
- Buttons that, when clicked, show the calculated dimensions in pixels.

---

## 🔧 jQuery Methods Used

| Method           | Description                                             |
|------------------|---------------------------------------------------------|
| `width()`        | Gets the **width** of the content only                  |
| `height()`       | Gets the **height** of the content only                 |
| `innerWidth()`   | Gets the width + **padding**                            |
| `innerHeight()`  | Gets the height + **padding**                           |
| `outerWidth()`   | Gets the width + padding + **border**                   |
| `outerHeight()`  | Gets the height + padding + **border**                  |

---

## 🎨 Visual Styling

- `#boxWrapper`: Represents the **outer border** (blue)
- `#box`: Represents the **padding** area (light blue)
- `#contentArea`: Represents the **content area** (white)
- Each area is labeled and color-coded to make dimensions easy to understand

---

## ▶️ How to Use

1. Open the `index.html` file in your browser.
2. Click on any of the buttons:
   - **Get Width** → Measures content width
   - **Get Inner Width** → Measures content + padding
   - **Get Outer Width** → Measures content + padding + border
   - ... same for height buttons
3. The result will display below the buttons.

---

## 🧠 Who Should Use This

Anyone learning:
- How box models work in web development
- How jQuery dimension methods measure different parts of an element

---
> Perfect for visual learners and jQuery beginners!
