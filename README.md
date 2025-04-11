# 💼 Abdul Malek - Portfolio Website

This is a personal portfolio website built using **HTML**, **CSS**, and **JavaScript**. It dynamically loads content from a `data.json` file to populate sections like About Me, Skills, Resume, and Projects.

---

## 💪 Features

- Responsive navigation bar
- Dynamic hero banner with name, description, and buttons
- About Me section with personal details
- Skills cards using custom icons
- Projects section dynamically loaded from JSON
- Resume section showing education and experience
- Contact form and social media links

---

## 📁 Project Structure

```plaintext
/
├── index.html
├── style.css
├── script.js
├── data.json
├── /images
│   ├── Abdul_Malek_2.png
│   └── /icons
│       ├── js.png
│       ├── react.png
│       ├── nodejs.png
│       └── mongo.png
```

---

## 📄 Description

### `index.html`
This is the main HTML file that renders the structure of the site. It includes:

- Hero section
- About section
- Skills cards
- Projects grid (populated via JS)
- Resume section
- Contact form

### `script.js`
Fetches data from `data.json` and injects it into the DOM to make the website dynamic and easier to update without modifying HTML.

---

## 📦 JSON Data Format

Example structure of `data.json`:

```json
{
  "banner": {
    "greeting": "Hi, I am",
    "name": "Mary Hardy",
    "description": "Friendly as an betrayed formerly he..."
  },
  "about": {
    "title": "About Me",
    "description": "I'm a designer & developer...",
    "details": {
      "name": "Abdul Malek",
      "email": "abdulmalekmonir97@gmail.com",
      "dob": "15 August 1997",
      "location": "Dhaka, Bangladesh"
    }
  },
  "skills": {
    "title": "What I Do",
    "description": "More than 10 years of experience...",
    "items": [
      {
        "title": "JavaScript",
        "description": "Aenean commodo ligula eget dolor.",
        "icon": "./images/icons/js.png"
      }
    ]
  },
  "resume": {
    "title": "A summary of My Resume",
    "education": [
      {
        "degree": "Master in Computer Engineering",
        "institution": "Harvard University / 2015 - 2017",
        "description": "Aenean commodo ligula eget dolor."
      }
    ],
    "experience": [
      {
        "position": "Sr. Front End Developer",
        "company": "Apple Inc / 2020 - Current",
        "description": "Aenean commodo ligula eget dolor."
      }
    ]
  },
  "projects": {
    "title": "My Projects",
    "description": "Here are some of my recent works...",
    "items": [
      {
        "name": "Project One",
        "description": "Short project description",
        "image": "./images/projects/project1.png",
        "link": "https://project-link.com"
      }
    ]
  }
}
```

---

## 🚀 How to Run

1. Clone the repository
2. Make sure all assets (`images`, `data.json`, etc.) are in the correct paths
3. Open `index.html` in a web browser

> No backend or server setup required.

---

## 👨‍💻 Author

**Abdul Malek**  
Email: `abdulmalekmonir97@gmail.com`

