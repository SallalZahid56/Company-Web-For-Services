A fully functional, responsive website for a company to display its services, team, and company information. This project includes a Home page, Services section, Team section, and About Us page. The frontend is developed using HTML, CSS, and JavaScript, and the backend is built using Node.js with Express. MySQL is used as the database to manage dynamic data.

🔗 Features Responsive Home Page

Services Section to showcase offerings

Team Section with member details

About Us Page with company information

Dynamic content loading from MySQL database

RESTful API built with Express

Clean and modern UI/UX

🛠 Tech Stack Frontend HTML5

CSS3

JavaScript (Vanilla)

Backend Node.js

Express.js

Database MySQL

📁 Project Structure php Copy Edit project-root/ │ ├── public/ # Static frontend files │ ├── css/ │ ├── js/ │ └── images/ │ ├── views/ # HTML templates or EJS (if used) │ └── *.html │ ├── routes/ # Express route handlers │ └── *.js │ ├── models/ # Database interaction layer (optional) │ └── *.js │ ├── db/ # MySQL connection config │ └── db.js │ ├── app.js # Main Express application ├── package.json # Node dependencies └── README.md # Project documentation 🚀 Getting Started Prerequisites Node.js & npm

MySQL server

Installation Clone the repository

bash Copy Edit git clone https://github.com/SallalZahid56/company-website.git cd company-website Install dependencies

bash Copy Edit npm install Set up MySQL database

Create a new MySQL database.

Import your schema and data (if applicable).

Update db/db.js with your database credentials.

Start the server

bash Copy Edit npm start Visit in browser

arduino Copy Edit http://localhost:3000 📦 API Endpoints (Example) Method Route Description GET / Home page GET /services List of services GET /team List of team members GET /about About Us content

📌 Notes Add environment variable support (using .env) for sensitive config like DB credentials.

Consider using a template engine (like EJS or Pug) for dynamic rendering if needed.

Add input validation and error handling for production use.

📄 License This project is licensed under the MIT License.
