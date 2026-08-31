🔎 Google Search Engine — Frontend Project

A simple recreation of the Google Search interface built using HTML and CSS.

This was my first self-made HTML/CSS project, created while I was learning the fundamentals of web development. The project recreates different Google search interfaces and connects the forms directly to Google's search endpoints.

It may be a small project, but it represents an important stage in my journey of learning how websites are structured and styled.

---

🌐 Project Overview

The project contains four different search interfaces:

🔍 Normal Search

A basic Google-style search page where you can enter a query and perform a normal Google search.

The search form sends the query to Google's search URL using the "q" parameter.

🖼️ Image Search

A dedicated image-search interface.

The page uses Google's "udm=2" parameter so that the submitted query opens Google's image-search results.

🤖 AI Search

An AI-search interface that uses Google's "udm=50" parameter to open the corresponding Google search mode.

⚙️ Advanced Search

An advanced search form with fields for:

- All these words
- Exact word or phrase
- None of these words
- Site or domain

These values are submitted using Google's advanced-search parameters such as "as_q", "as_epq", "as_eq", and "as_sitesearch".

---

🛠️ Technologies Used

- HTML5
- CSS3
- Git
- GitHub

No JavaScript or backend server is used in this project.

---

📁 Project Structure

Google_search_Engine/
│
├── index/
│   ├── index.html
│   ├── Image.html
│   ├── ai_search.html
│   └── adv_search.html
│
├── styleing/
│   ├── style.css
│   └── style_adv.css
│
├── .gitignore
└── Readme.md

The project separates the HTML pages from their CSS files, with a dedicated stylesheet for the advanced-search page.

---

✨ Features

- 🔍 Normal Google search
- 🖼️ Google image search
- 🤖 Google AI search
- ⚙️ Google advanced search
- 🔗 Navigation between the different search modes
- 🎨 Custom dark-themed interface
- 📱 Basic viewport configuration for different screen sizes
- 🧩 Separate HTML and CSS files

The main search page also includes navigation links to the image, AI, and advanced search pages.

---

🎨 Design

I created the interface from scratch using HTML and CSS rather than using a frontend framework.

The project uses a dark background, white typography, rounded search inputs, and simple hover effects for buttons and navigation links.

The advanced-search page has a separate layout and stylesheet to accommodate its additional search fields.

---

📚 What I Learned

This project was mainly about getting comfortable with the fundamentals of frontend development.

While building it, I learned about:

- HTML document structure
- Forms and input elements
- Form "action" URLs
- Query parameters
- HTML links and navigation
- CSS selectors
- CSS layouts
- Styling forms and buttons
- Hover effects
- Linking external pages through forms
- Organizing HTML and CSS into separate directories
- Using Git and GitHub to manage a project

One particularly useful thing I learned was that a form doesn't necessarily need a backend of its own. By constructing the appropriate URL and query parameters, a form can send its data directly to an external service.

---

🧠 How It Works

The project doesn't implement a search algorithm or maintain its own search index.

Instead, the HTML forms construct requests that are sent to Google's search service.

For example, the normal search essentially follows this pattern:

User enters query
        ↓
HTML form
        ↓
Google search URL
        ↓
Google processes the query
        ↓
Search results

The same idea is used for the image and AI search modes, with different Google parameters controlling the search mode.

---

🚧 Limitations

This is a frontend recreation, not an actual search engine.

The project currently:

- Does not have its own search algorithm
- Does not crawl or index websites
- Does not have a database
- Does not have a backend
- Does not implement authentication
- Does not implement JavaScript-based interactions
- Relies on Google's existing search service for the actual results

So the name "Google Search Engine" describes the project concept, but technically this project is closer to a Google Search interface recreation.

---

🚀 Future Improvements

As I continue learning web development, I would like to improve this project by adding:

- [ ] Responsive design
- [ ] Better mobile support
- [ ] More accurate Google-style UI
- [ ] JavaScript interactions
- [ ] Search suggestions
- [ ] Better accessibility
- [ ] Cleaner and more maintainable CSS
- [ ] Improved folder and file naming
- [ ] Deployment as a live website

The goal isn't necessarily to turn this into a real search engine, but to use it as a starting point for learning more advanced frontend and eventually backend development.

---

❤️ Why This Project Matters

This project is special to me because it was one of my first projects where I stopped just learning syntax and actually tried to build something myself.

It is simple.

It has plenty of things I would do differently today.

And that's exactly why I want to keep it.

As I build more projects, this repository will serve as a reminder of where I started and how my coding skills develop over time.

«Every developer has a first project. This is mine. 🚀»

---

👨‍💻 Author

Nikhil

Student and aspiring software developer.

Currently learning programming, web development, and computer science fundamentals.

---

📌 Project Status

🟢 Completed — Beginner Learning Project

This repository is mainly kept as part of my learning journey and as a record of my progress with HTML, CSS, Git, and GitHub.
