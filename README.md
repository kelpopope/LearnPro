# LearnPro — Online Learning Platform

![LearnPro Hero](images/hero.webp)

A modern, responsive educational website featuring both static “Featured” courses (with built-in quizzes) and an API-loaded “More Courses” section. Built with plain HTML, CSS, JavaScript, and Bootstrap 5, LearnPro demonstrates interactive elements (accordions, modals, progress bars), client-side form validation, and dynamic data fetching.

---



## About

LearnPro is a single-page-style educational platform prototype, featuring:

- **Static “Featured” Courses**:  
  - **Web Development**, **UI/UX Design**, and **Digital Marketing**  
  - Each has a 10-question multiple-choice quiz with real-time progress tracking and immediate feedback  
- **API-Loaded Courses**:  
  - Dynamically fetches additional course cards from `https://jsonplaceholder.typicode.com/posts`  
  - Displays first six items with placeholder images and “View Details” modals  
- **Client-Side Form Validation**:  
  - Contact page (Name, Email, Message)  
  - Sign Up page (First Name, Last Name, Email, Password/Confirm, Area of Interest, Terms checkbox)  
  - Custom password-match check using JavaScript  
- **Responsive Design**:  
  - Mobile-first approach with Bootstrap 5 grid, Flexbox, and CSS Grid  
  - Custom media query to adjust hero heading on small screens  
- **Interactive Components**:  
  - Bootstrap accordion for course overviews  
  - Modals for form success messages and API course details  
  - Progress bars updating as quiz answers are evaluated

All images are lazy-loaded (`loading="lazy"`) and stored in **WebP** or **SVG** format for optimized performance.

---

## Features

- **Semantic HTML Structure**:  
  `<header>`, `<main>`, `<section>`, `<footer>` for accessibility and SEO
- **Responsive, Mobile-First Layout** using Bootstrap 5  
- **Accordion Components** for course overviews  
- **10-Question Quizzes** on each static course page with:  
  - Radio inputs (`<input type="radio">`) and `data-correct="true"` attributes  
  - Immediate “Correct!”/“Incorrect” feedback  
  - Real-time progress bar calculation (`style.width = X%`)  
- **API Integration** to fetch and display six additional courses, plus modals for details  
- **Client-Side Validation** (`checkValidity()` and `setCustomValidity()`) on “Contact” and “Sign Up” forms  
- **Lazy-Loaded Images** (`loading="lazy"`) to improve page load performance  
- **Custom Blue-Theme** overrides in `css/style.css` for `.accordion-button` and `.progress-bar`

---

## Technology Stack

- **HTML5**  
- **CSS3** (Custom + [Bootstrap 5](https://getbootstrap.com/))  
- **JavaScript (ES6)**  
- **Bootstrap 5** (v5.3.0) via CDN  
- **Public API**: `https://jsonplaceholder.typicode.com/posts` for placeholder courses  
- **Image Formats**: WebP (illustrations/photos) and SVG (logo)  
- **No build tools required**—entirely static pages

---

## Folder Structure

