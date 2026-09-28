# ☕ Organic Coffee: hackathon website

A multi-page, responsive website for a fictional **fair-trade coffee brand**, built during the **Winc Academy front-end hackathon**. It's built with plain HTML and CSS, with no frameworks.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## Pages

| Page | Contents |
|---|---|
| **Home** (`Index.html`) | Full-screen hero with a background image and a headline |
| **Sign up** (`Signup.html`) | Sign-up form (text, email, phone, date, radio buttons, textarea) and an image slider |
| **Discover** (`Discover.html`) | Brand story sections and an embedded YouTube video |
| **About us** (`About us.html`) | Team section with photos, bios and Tweet buttons |

## Techniques used

- Semantic HTML5 (`nav`, `header`, `main`, `footer`).
- Responsive layout with the viewport meta tag, Flexbox and media queries.
- A navigation bar that highlights the active page.
- HTML forms with several input types and client-side validation attributes.
- A pure-CSS image slider.
- Social icons with Font Awesome, and embedded third-party widgets (YouTube, Twitter).

## Run locally

No build step is needed. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## What I learned

- Planning and building a complete multi-page site under hackathon time pressure.
- **File names are case-sensitive on web servers.** Links such as `styles.css` versus `Styles.css` work on Windows and macOS but break once the site is hosted on Linux.
