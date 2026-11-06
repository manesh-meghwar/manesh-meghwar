# Manesh Kumar

**Applied AI/ML researcher and software engineer**

Personal portfolio for software engineering work and graduate research in machine learning, recommender systems, and computational biology.

**Live site:** [manesh-meghwar.github.io/manesh-portfolio](https://manesh-meghwar.github.io/manesh-portfolio/)

## About

Manesh Kumar is a software engineer from Tharparkar, Pakistan, and an MSc Computer Science student at the Ocean University of China. He graduated in Software Engineering in 2018 and spent more than three years building web applications, REST APIs, and data-driven systems. His current research applies deep learning to proteins, ligands, and molecular interactions, alongside machine learning, data science, generative AI, RAG, LangChain, LangGraph, and agentic AI.

## Site

| Page | File | What it shows |
| --- | --- | --- |
| Home | `index.html` | Introduction and current focus |
| Resume | `resume.html` | Experience, education, and skills |
| Projects | `projects.html` | Selected software and ML work |
| Blog | `blog.html` | Writing |
| Certificates | `certificates.html` | Credentials |
| Contact | `contact.html` | LinkedIn, email, GitHub, and other profiles |

Project cards are rendered from the `projects` array in `js/main.js`.

## Selected work

| Project | What it is | Link |
| --- | --- | --- |
| BookWise | Flask book recommender. Popularity ranking, item-based collaborative filtering, and cosine similarity over 1.14M+ Book-Crossing interactions. | [Repository](https://github.com/manesh-meghwar/book-recommendation-system) |
| Olympics Insight | Streamlit analytics dashboard over 271,000+ athlete-event records, built with Python, Pandas, and Plotly. | [Live demo](https://olympics-insight-dashboard.onrender.com/) |
| Birdme | REST APIs in PHP and Laravel for an Android app: invoices, customers, products, reporting, and payments. | [Play Store](https://play.google.com/store/apps/details?id=com.birdme) |
| The Darzee | Backend, REST APIs, MySQL, and an admin panel for an on-demand tailoring platform. | On the Projects page |
| Objexyz | WordPress site for 3D printers and on-demand printing services (2021). | [objexyz.com](https://objexyz.com) |
| Preontech | Corporate WordPress site for platforms, IoT, big data, and AI (2021). | [preontech.com](https://preontech.com/) |

The Projects page also includes MyCart Inventory, a property management system, MyWater ATM, vehicle number-plate recognition, and a learning management system.

## Stack

HTML5, CSS3, Bootstrap 5.3, Bootstrap Icons, and vanilla JavaScript. There is no React, Node, npm, database, or build step. Bootstrap is loaded from a CDN, so a local preview needs an internet connection.

## Run it locally

1. Clone the repository.
2. Open `index.html` in a browser.

A local static server, such as the VS Code Live Server extension, is optional. It is useful when you want clean paths for images and navigation.

## Edit the content

| Change | File |
| --- | --- |
| Home and about text | `index.html` |
| Resume | `resume.html` |
| Project titles, descriptions, images, and links | `js/main.js` |
| Blog posts | `blog.html` |
| Certificates | `certificates.html` |
| Contact links | `contact.html` |
| Colors and layout | `css/style.css` |
| Navigation and footer | `js/main.js` |
| Portrait | `assets/profile.jpg` |

To add an introduction video, place an MP4 at `assets/introduction-video.mp4`. The resume page picks it up automatically. A horizontal 16:9 file under 25 MB, about 60–90 seconds, fits the player.

## Deploy

Pushes to `master` deploy the site through `.github/workflows/static.yml`. GitHub Pages serves the repository root at:

https://manesh-meghwar.github.io/manesh-portfolio/

## Layout

```text
index.html            Home
resume.html           Resume
projects.html         Projects page
blog.html             Blog
certificates.html     Certificates
contact.html          Contact
css/style.css         Styles
js/main.js            Navigation, footer, and project data
assets/               Portrait, project images, blog images, certificates
.github/workflows/    GitHub Pages deploy
