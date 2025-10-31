# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

# Frontend Mentor - Testimonials grid section

This project is inspired by Frontend Mentor challenges.
It demonstrates a responsive CSS Grid layout for user cards using only HTML and CSS, without JavaScript.

---

## 🧠 About The Project

The layout showcases multiple user testimonials arranged within a responsive grid container.
Each card contains user details such as name, title, and testimonial.
The goal is to practice CSS Grid, responsive design, and color contrast handling.

---

## 💻 Built With

- HTML5 semantic structure
- CSS3 (Grid layout and positioning)
- Custom CSS variables for colors and spacing
- Media Queries for mobile responsiveness

---

## 📱 Responsive Design

### Desktop (Default)

```css
.container {
  width: 100%;
  display: grid;
  margin: 20px;
  padding: 20px 30px;
  grid-template-columns: repeat(5, 1fr);
  grid-template-rows: auto auto auto;
  column-gap: 25px;
  row-gap: 25px;
  place-content: center;
}
```

### Mobile (≤ 375px)

```css
@media (max-width: 375px) {
  .container {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: auto;
    justify-items: center;
    padding: 14px;
    gap: 16px;
  }

  .user-card-1,
  .user-card-2,
  .user-card-3,
  .user-card-4,
  .user-card-5 {
    width: 100%;
    max-width: 320px;
    height: auto;
    position: static;
    transform: none;
    grid-column: 1;
    grid-row: auto;
  }
}
```

---

## 🚀 How To Use

1. Clone or download this repository.
2. Open the index.html file in your browser.
3. Modify style.css to customize colors or layout if needed.

---

## 🎯 Key Learnings

- Using CSS Grid to build flexible multi-column layouts.
- Creating mobile-friendly designs using media queries.
- Managing consistent spacing and colors with CSS variables.
- Practicing clean, modular CSS code organization.

---

## 🚀 Live Demo

[[live demo link ]()]

## 🧑‍💻 Author

- Frontend Mentor – [@SaharQ1986](https://www.frontendmentor.io/profile/SaharQ1986)
- GitHub – [@SaharQ1986](https://github.com/SaharQ1986/Frontend-Mentor---Testimonials-grid-section.git)

---

## 🪶 Acknowledgments

Design concept inspired by [Frontend Mentor](https://www.frontendmentor.io/).
