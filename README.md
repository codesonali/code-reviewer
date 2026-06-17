AI-Powered Code Reviewer

An intelligent web application that analyzes source code and provides AI-generated feedback on code quality, bugs, syntax issues, optimization opportunities, and algorithm complexity. Built using React, Node.js, Express, and OpenRouter API.

Live Demo

🔗 Project Link: https://code-reviewer-ten-eosin.vercel.app/

Features
Multi-language code analysis (Java, Python, C++)
AI-powered code reviews
Syntax issue detection
Bug identification and suggestions
Code quality improvements
Time Complexity (Big-O) analysis
Space Complexity evaluation
Optimized code recommendations
Syntax highlighting for better readability
Clean and responsive user interface
Real-time review generation
Tech Stack
Frontend
React.js
Vite
JavaScript
Axios
React Markdown
PrismJS
HTML5
CSS3
Backend
Node.js
Express.js
REST APIs
AI Integration
OpenRouter API
Large Language Models (LLMs)
Prompt Engineering
Deployment
Vercel
GitHub
How It Works
Select a programming language.
Paste or write code in the editor.
Submit the code for analysis.
The backend sends the code to an AI model through OpenRouter API.
The AI reviews the code and generates:
Syntax analysis
Bug detection
Improvement suggestions
Time complexity analysis
Space complexity analysis
Optimized code recommendations
Results are displayed in a structured and readable format.
Project Structure
code-reviewer/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│   └── package.json
│
└── README.md
Installation
Clone the Repository
git clone https://github.com/your-username/code-reviewer.git
cd code-reviewer
Frontend Setup
cd frontend
npm install
npm run dev
Backend Setup
cd backend
npm install
npm start
Environment Variables

Create a .env file in the backend directory:

OPENROUTER_API_KEY=your_api_key_here
PORT=5000
Example Review Output
✓ Syntax Analysis
✓ Bug Detection
✓ Code Quality Suggestions
✓ Time Complexity: O(n)
✓ Space Complexity: O(1)
✓ Optimized Solution
Future Enhancements
User authentication
Review history
Download review reports
Code similarity detection
ATS-style coding score
Dark/Light theme toggle
Additional language support
Local AI model integration using Ollama
Performance analytics dashboard
Learning Outcomes
Full Stack Web Development
REST API Integration
AI Application Development
Prompt Engineering
React State Management
Backend Development with Express
API Security and Environment Variables
Deployment and Production Hosting
Author

Sonali Srivastava

B.Tech CSE Student
Web Development & DSA Enthusiast
License

This project is open-source and available under the MIT License.
