🚀 Enterprise Service Desk & Defect Management Portal
📖 Overview

The Enterprise Service Desk & Defect Management Portal is a full-stack web application designed to streamline IT support operations, incident management, and software defect tracking within an enterprise environment. This platform provides a centralized hub for users to submit support requests, report software defects, monitor ticket progress, and collaborate with support teams.

💡 This project demonstrates enterprise-level software development practices, including secure authentication, role-based access control, workflow management, cloud deployment, and modern web technologies.

✨ Features
🎫 Service Desk Management
Create and manage support tickets
Track ticket status in real time
Assign tickets to support personnel
Set ticket priority levels
Add comments and updates
🐞 Defect Management
Report software defects and bugs
Categorize defects by severity
Track defect lifecycle
Assign defects to development teams
Monitor resolution progress
👤 User Management
Secure user authentication
Role-based access control
User profile management
Administrative controls
📊 Dashboard & Reporting
Ticket analytics dashboard
Defect tracking metrics
Open vs. resolved ticket reports
Performance monitoring
Search and filter functionality
🔒 Security
Authentication and authorization
Protected API endpoints
Secure database interactions
Input validation and error handling
🛠️ Technology Stack
🎨 Frontend
React.js
JavaScript (ES6+)
HTML5
CSS3
⚙️ Backend
Python
Flask
🗄️ Database
PostgreSQL
MySQL
☁️ Cloud & DevOps
AWS EC2
AWS S3
Git
GitHub
🏗️ System Architecture
🖥️ Frontend (React)
          │
          ▼
⚙️ Backend API (Flask)
          │
          ▼
🗄️ PostgreSQL / MySQL
          │
          ▼
☁️ AWS Infrastructure (EC2 & S3)
🚀 Installation
📥 Clone the Repository
git clone https://github.com/yourusername/enterprise-service-desk-portal.git

cd enterprise-service-desk-portal
⚙️ Backend Setup

Create a virtual environment:

python -m venv venv

Activate the virtual environment:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate

Install dependencies:

pip install -r requirements.txt

Run the Flask server:

python app.py
🎨 Frontend Setup

Navigate to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the development server:

npm run dev
🔧 Database Configuration

Create a PostgreSQL or MySQL database.

Example .env file:

DB_HOST=localhost
DB_NAME=service_desk
DB_USER=admin
DB_PASSWORD=password
DB_PORT=5432
🌐 API Endpoints
🎫 Tickets
Method	Endpoint	Description
GET	/tickets	Retrieve all tickets
POST	/tickets	Create a new ticket
GET	/tickets/:id	Retrieve ticket details
PUT	/tickets/:id	Update ticket
DELETE	/tickets/:id	Delete ticket
🐞 Defects
Method	Endpoint	Description
GET	/defects	Retrieve all defects
POST	/defects	Create a defect
GET	/defects/:id	Retrieve defect details
PUT	/defects/:id	Update defect
DELETE	/defects/:id	Delete defect
📈 Future Enhancements
📧 Email notifications
🤖 AI-powered ticket categorization
⏱️ SLA tracking and monitoring
📚 Knowledge base integration
📱 Mobile application support
📊 Advanced analytics dashboards
🔔 Real-time notifications
🌍 Multi-language support
🎯 Learning Objectives

This project demonstrates:

✅ Full-Stack Web Development

✅ RESTful API Design

✅ Database Integration

✅ Authentication & Authorization

✅ Enterprise Ticket Management Workflows

✅ Defect Lifecycle Management

✅ AWS Cloud Deployment

✅ Agile Development Practices

✅ Software Testing & Quality Assurance

📸 Screenshots

Add screenshots of your application here:

👨‍💻 Author
Quanda Grant

🎓 Junior Software Developer

🧪 QA Analyst

💻 Full-Stack Developer

📚 Codex Academy Graduate

🌟 Passionate about building scalable software solutions and improving user experiences through technology.
