An AI Article Summarizer Website

📋 Table of Contents
🤖 Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start
🕸️ Snippets
🔗 Links
🚀 More
🚨 Tutorial
This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, JavaScript Mastery.

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!



🤖 Introduction
Summarize any kind of article with just one click using the powerful OpenAI model.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 27k+ members. It's a place where people help each other out.



⚙️ Tech Stack
React.js
TypeScript
Redux Toolkit
Tailwind CSS
🔋 Features
👉 Modern User Interface: A modern and user-friendly interface, offering an intuitive experience for users.

👉 Summary Generation: Users can input the URL of a lengthy article, and the web app utilizes AI to provide a concise summary of the article content.

👉 History Saving with Local Storage: The app includes a history feature, allowing users to save summaries locally, providing a convenient way to revisit and manage their reading history.

👉 Copy to Clipboard Functionality: Enables users to easily share or store the summarized content by copying it to their clipboard.

👉 Advanced RTK Query API Requests: Utilizes the advanced capabilities of Redux Toolkit (RTK) Query for making API requests. These requests fire conditionally based on specific criteria, optimizing data fetching and management.

and many more, including code architecture and reusability

🤸 Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/adrianhajdin/project_ai_summarizer.git
cd project_ai_summarizer
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

VITE_RAPID_API_ARTICLE_KEY=
Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the Rapid API website.

Running the Project

npm run dev
Open http://localhost:5173 in your browser to view the project.

🕸️ Snippets
App.css
index.html

API Used
This project uses an AI-based article summarization API from RapidAPI. The API provides the ability to generate summaries from long-form content like articles or blog posts.

You can find more details about the API here.

Contributing
If you'd like to contribute to this project, feel free to open a pull request or raise an issue. All contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.
