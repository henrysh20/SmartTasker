# SmartTasker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview

SmartTasker is an innovative task management application powered by AI to help individuals and teams organize, prioritize, and automate their tasks effortlessly. Whether you're managing a personal to-do list or coordinating projects, SmartTasker adapts intelligently to optimize your productivity.

## Features

- AI-driven task prioritization and suggestions
- Smart reminders and deadline tracking
- Collaborative task sharing with team members
- Customizable workflow automation rules
- Intuitive drag-and-drop task board
- Dark and light mode support

## Tech Stack

- Frontend: React.js
- Backend: Node.js & Express
- Database: MongoDB
- AI Integration: OpenAI GPT-4 API
- Authentication: JWT

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/henrysh20/SmartTasker.git
   ```

2. Navigate to the project folder:

   ```bash
   cd SmartTasker
   ```

3. Install dependencies for backend and frontend:

   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

4. Create a `.env` file in the `backend` directory and add your environment variables:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   OPENAI_API_KEY=your_openai_api_key
   JWT_SECRET=your_jwt_secret
   ```

5. Start the backend server:

   ```bash
   cd ../backend
   npm start
   ```

6. Start the frontend application:

   ```bash
   cd ../frontend
   npm start
   ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Register a new account or log in.
3. Start creating tasks, set priorities, and explore AI-powered suggestions.
4. Invite team members to collaborate on shared projects.
5. Customize automation rules to streamline repetitive tasks.

## Screenshots

![Dashboard](https://via.placeholder.com/800x400?text=SmartTasker+Dashboard)

![Task Board](https://via.placeholder.com/800x400?text=Task+Board)

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository on GitHub: [https://github.com/henrysh20/SmartTasker](https://github.com/henrysh20/SmartTasker)
2. Create your feature branch:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add some feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeature
   ```

5. Open a pull request detailing your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Author

👤 **Henry Shaw**  
GitHub: [https://github.com/henrysh20](https://github.com/henrysh20)  

---

Thank you for checking out SmartTasker! 🚀
