# Frontend Mentor - Profile Card Component

This is a solution to the [Profile Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 🧠 About The Project

A simple and responsive profile card built using only HTML and CSS.
This project focuses on layout, positioning, and visual hierarchy using Flexbox and modern CSS properties.

---

## 💻 Built With

- HTML5 semantic structure
- CSS3 (Flexbox, position, box-shadow, and custom properties)
- Responsive design with media queries

---

## 📱 Mobile Design Settings (max-width: 375px)

```css
@media (max-width: 375px) {
  body {
    margin: 0;
    padding: 0.5rem;
    display: flex;
    flex-direction: column;
    align-items: center;

    background-position: left -140px top -160px, right -140px bottom -170px;
    background-repeat: no-repeat;
    background-size: contain;
  }
  .card {
    width: 90%;
    text-align: center;
    border-radius: 10px;
    margin: 1.5rem auto;
  }
  .top-card img {
    top: 50%;
    left: 0;
    transform: translate(100%, 70%);
  }
  .bottom-card .name {
    font-size: 18px;
  }
  .bottom-card .age {
    margin-left: 8px;
    font-size: 17px;
  }
  .bottom-card .location {
    font-size: 16px;
    margin: 3px;
    margin-bottom: 30px;
  }
  dd {
    margin: 0;
    font-size: 16px;
  }
  dt {
    font-size: 10px;
  }
}
```

---

## 🚀 Live Demo

[[live demo link ](https://tourmaline-lokum-6e4541.netlify.app/)]

---

## 🧩 How To Run

1. Clone this repository
   ```bash
   git clone https://github.com/SaharQ1986/Frontend-Mentor---Profile-Card-Component.git
   ```
2. Open `index.html` in your browser.

---

## 🧑💻 Author

- Frontend Mentor – [@SaharQ1986](https://www.frontendmentor.io/profile/SaharQ1986)
- GitHub – [@SaharQ1986](https://github.com/SaharQ1986)

---

## 🪶 Acknowledgments

Design and assets provided by [Frontend Mentor](https://www.frontendmentor.io/).
