Code Sage 🧙‍♂️ - Your AI-Powered Code Assistant

Live Demo: https://prajjwal-01.github.io/code-sage-project/

Project Overview
Code Sage is a web-based application designed to assist developers by leveraging the power of generative AI. It acts as an on-demand pair programmer and code reviewer, providing a suite of tools to improve code quality, efficiency, and understanding. This project solves a common developer pain point: the need for a quick, intelligent second opinion on code, without interrupting a colleague's workflow.

This application was built from scratch to demonstrate a practical, full-stack understanding of modern web development and AI integration.

Core Features
Code Sage offers a range of powerful, AI-driven actions to enhance any code snippet:

Find Bugs: Analyzes code for logical errors, potential runtime issues, and security vulnerabilities, providing detailed explanations and suggested fixes.

 Refactor & Optimize: Rewrites code to be more efficient, readable, and idiomatic to the language, following modern best practices.

 Generate Unit Tests: Automatically creates a suite of unit tests using popular frameworks (like Pytest for Python or Jest for JavaScript) to ensure code reliability.

Document Code: Generates clear, concise documentation in standard formats (like JSDoc or Python Docstrings) to explain the code's purpose, parameters, and return values.

Translate Language: Translates code from one programming language to another, highlighting key idiomatic changes.


Tech Stack
This project was built using a modern, single-page application architecture.

Frontend:
React: For building a dynamic and component-based user interface.
Tailwind CSS: For professional, responsive, and utility-first styling.
Marked.js: For rendering the AI's Markdown responses into clean HTML.

AI Integration:
Google Gemini API: The core AI engine for all code analysis and generation tasks.
Deployment:
GitHub Pages: For fast, reliable, and free static site hosting.

How to Run Locally
To get a local copy up and running, follow these simple steps.

Clone the repository:
git clone https://github.com/prajjwal-01/code-sage-project.git
Get a free Gemini API Key at Google AI Studio.
Open index.html in your code editor.
Add your API Key:
Find the line: const apiKey = "PASTE_YOUR_API_KEY_HERE";
Replace "PASTE_YOUR_API_KEY_HERE" with your actual key.
Open the index.html file in your web browser.

Why This Project? 
This project was strategically chosen to demonstrate a range of highly sought-after skills:
Full-Stack Thinking: While this is a frontend application, it's architected with security and best practices in mind (e.g., handling API keys, managing state).
Advanced Prompt Engineering: The quality of the AI's output is a direct result of carefully crafted, role-based prompts that instruct the model to act as a security auditor, a senior developer, or a technical writer. This goes beyond simple API calls.

Solving a Real-World Problem: This tool directly addresses the daily challenges of software developers, showing an understanding of the development lifecycle.

Focus on Modern Best Practices: The inclusion of features like "Generate Unit Tests" and "Refactor" highlights a commitment to code quality, testing, and maintainability.
