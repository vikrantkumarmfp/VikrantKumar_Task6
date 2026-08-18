# LaundryMart Login Page

A responsive login-page project built with **HTML and CSS** as part of my web development learning journey.

## 📌 Project Overview

This project recreates a modern LaundryMart login interface with:

- A LaundryMart promotional image on the left
- A login form on the right
- Email and password fields
- Form validation using HTML attributes
- Forgot Password button
- Login button
- Register Now option
- Responsive viewport setup

## 🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox

## 📂 Project Structure

```text
LaundryMart-Login/
│
├── index.html
├── index.css
└── laundryMart.png
```

## ✨ HTML Features

### Semantic Form Structure

The login form uses:

- `<form>`
- `<label>`
- `<input>`
- `<button>`
- `<section>`
- `<div>`

### Form Validation

The email field uses:

```html
<input id="email" type="email" minlength="5" maxlength="28" required />
```

The password field uses:

```html
<input id="password" type="password" minlength="5" maxlength="28" required />
```

This provides basic browser-level validation without JavaScript.

## 🎨 CSS Features

### Universal Reset

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

`box-sizing: border-box` was used to make width and height calculations easier when working with padding and borders.

### Two-Column Layout

The main container uses Flexbox:

```css
.container {
  height: 100vh;
  display: flex;
}
```

The page is divided into two equal sections:

```css
.left {
  width: 50vw;
}

.right {
  width: 50vw;
}
```

### Form Layout

Flexbox is also used to organize the form elements vertically:

```css
#login form {
  display: flex;
  flex-direction: column;
  gap: 12px;
}
```

### Button Styling

The Login and Register buttons are styled using CSS with:

- Background colors
- Border radius
- Padding
- Cursor changes
- Font styling

## 📚 Learning Journey

This project is part of my **web development learning path**. It was created to practice and strengthen my understanding of HTML forms and CSS layouts.

### Concepts Practiced

- HTML document structure
- Semantic sections
- Forms and form controls
- Labels and input fields
- HTML form validation
- `required`
- `minlength`
- `maxlength`
- Input types such as `email` and `password`
- CSS reset
- `box-sizing`
- Flexbox
- `flex-direction`
- `align-items`
- `justify-content`
- `gap`
- CSS selectors
- IDs and classes
- Button styling
- Image sizing
- Viewport units (`vh` and `vw`)

## 🎯 What I Learned

Through this project, I practiced building a complete login interface instead of working with isolated HTML or CSS examples. I also learned how Flexbox can be used to divide a page into columns and organize form elements.

## 🚀 Future Improvements

- Add JavaScript form validation
- Implement actual login functionality
- Add password visibility toggle
- Make the layout fully responsive for mobile devices
- Add a functional Forgot Password flow
- Add a separate registration page
- Improve accessibility
- Add hover and focus states

## 👨‍💻 Author

**Vikrant Kumar**

This project is part of my journey toward becoming a **Full Stack Web Developer**.
