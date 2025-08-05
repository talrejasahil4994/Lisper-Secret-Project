# Lisper-Secret-Project
Lisper is a web app that fetches and displays random anonymous secrets using a glowing animated card. Built with Node.js, Express, EJS, and Axios, it combines dynamic data with stylish visuals for a fun and modern experience.

# Lisper

Lisper is a fun and stylish web app that fetches random anonymous secrets and displays them with a glowing card-style animation. It uses Express.js on the backend and EJS templating on the frontend, with data fetched from the [Secrets API by App Brewery](https://secrets-api.appbrewery.com/).

## ✨ Features

- Fetches a random secret from an external API
- Visually engaging card design with animated reveal
- Styled with modern CSS and Google Fonts
- Clean and minimal EJS templating

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **EJS (Embedded JavaScript Templates)**
- **Axios**
- **HTML5/CSS3**

## 📂 Project Structure

Lisper/
├── public/
│ └── styles/
│ └── main.css # Main styles for the glowing card
├── views/
│ └── index.ejs # EJS template for rendering secret and username
├── index.js # Express server with route to fetch and display secret
├── images/
│ └── whisper-img.jpg # Background image for the card (you should add this)


## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/lisper.git
cd lisper
Install dependencies:

bash....

npm install express axios
Run the server:

bash...

node index.js
Open your browser and go to:
http://localhost:4000
