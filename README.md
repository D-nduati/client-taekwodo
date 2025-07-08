# 🥋 Taekwondo Application
The Taekwondo Application is a comprehensive digital platform built
 to streamline operations for martial arts academies and enhance the experience for
 students, coaches, and administrators.
 It provides tools for **managing users, events, rankings, quizzes, achievements, media content, and more **— all in one place.

**🚀 Key Features**
**User Management**
Manage student, instructor, and admin profiles with role-based access and detailed profile sections (skills, settings, achievements).
**Event Management**
Create, update, and manage Taekwondo events such as belt promotions, tournaments, and training camps.

**Quizzes & Rankings**
Test knowledge using quizzes, track scores, and rank students based on performance.

**Achievements & Progress Tracking**
Record individual progress, skill level, belt rank, and competition achievements.

**Media Sharing**
Upload and interact with photos and videos related to trainings and events — including likes and comments.

**Telemedicine & Feedback (Optional Modules)**
Add-ons for virtual sessions, coaching reviews, and injury reports.

**Admin Console**
Curate data across all modules with full CRUD capabilities and moderation tools.

**🛠️ Tech Stack**
Frontend: React.js + Ant Design + Umi.js

Backend: Node.js + Express.js

Database: Microsoft SQL Server (MSSQL)

**API Communication: RESTful APIs using Axios**

This monorepo includes both the client (frontend) and server (backend) code.

**⚙️ Getting Started**
1. Clone the Repository

git clone https://github.com/D-nduati/taekwondo-app/
**2. Setting Up the Frontend (Client)**
**📦 Prerequisites**

Ensure you have installed:
Node.js
npm

**🚀 Steps**

cd taekwondo-app/client
npm install
npm start
This will start the frontend on http://localhost:3000.

**3. Setting Up the Backend (Server)**
**📦 Prerequisites**
Node.js installed
MSSQL Server set up and running
Create a .env file with your database credentials and port configuration.

**🚀 Steps**
cd ../backend
npm install
npm run dev
The server will run on http://localhost:5000 (or your defined port).

**🗃️ Sample .env File**

DB_USER=your_db_username
DB_PASSWORD=your_db_password
DB_SERVER=localhost
DB_DATABASE=taekwondo_db
PORT=5000

**🧩 Modules Breakdown**

**Module	Description**
Users	Add/edit/view members, instructors, and roles
Events	Manage Taekwondo events (CRUD)
Posts	Share training moments via media
Videos	Upload and view training videos
Quizzes	Create and take Taekwondo quizzes
Rankings	Generate and view student rankings
Achievements	Track belt promotions, medals, etc.
Settings	Manage user preferences and app configurations

**💬 Testimonials**
“This platform transformed the way we manage tournaments and students’ progress. It's like having a digital dojo!” — Coach Kimani

“As a student, I loved the quizzes and the way I could track my belt journey!” — Juma, Green Belt

**📬 Contact**
Got feedback or want to contribute? Open an issue or pull request — we’d love to collaborate!
