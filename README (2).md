# AI-Driven Career Guidance System

An AI-powered web application that provides personalized career guidance, skill recommendations, and job insights.  
Built with Next.js, Prisma, and Tailwind CSS for a modern, scalable, and responsive experience.

---

## Features
- AI-powered career advice and recommendations  
- Skill and job matching system  
- Responsive and clean UI with Tailwind CSS  
- Database management using Prisma ORM  
- Scalable Next.js architecture  

---

## Tech Stack
- **Frontend**: Next.js (React Framework)  
- **Backend**: Node.js (with Next.js API routes)  
- **Database**: Prisma + SQLite/PostgreSQL/MySQL  
- **Styling**: Tailwind CSS  
- **Deployment**: Vercel / Netlify / Docker  

---

## Project Structure
ai-driven-career-guidance-system/
│── app/ # Next.js application code
│── components/ # Reusable UI components
│── lib/ # Helper functions
│── prisma/ # Database schema and migrations
│── public/ # Static assets
│── styles/ # Global styles (Tailwind)
│── package.json # Project dependencies

yaml
Copy code

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AI-Driven-Career-Guidance-System.git
   cd AI-Driven-Career-Guidance-System
Install dependencies:

bash
Copy code
npm install
Set up the database:

bash
Copy code
npx prisma migrate dev --name init
Run the development server:

bash
Copy code
npm run dev
Application will be available at: http://localhost:3000

Roadmap
Integrate AI career recommendation engine

Add user authentication

Support multiple databases (PostgreSQL, MongoDB)
