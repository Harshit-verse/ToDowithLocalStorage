\React Todo App with Local Storage

A responsive Todo application built using React that allows users to add, edit, and delete tasks.
All tasks are persisted using localStorage, ensuring data remains available even after page refresh.

🔗 Live Demo:
https://to-dowith-local-storage.vercel.app

📂 GitHub Repository:
https://github.com/Harshit-verse/ToDowithLocalStorage

🚀 Features

Add new tasks

Edit existing tasks

Delete tasks

Persistent storage using localStorage

Real-time UI updates with React state

Deployed on Vercel

🛠️ Tech Stack

React

JavaScript (ES6+)

HTML5

CSS3

Vercel (Deployment)

📦 Installation & Local Setup

Clone the repository:

git clone https://github.com/Harshit-verse/ToDowithLocalStorage.git


Navigate into the project directory:

cd ToDowithLocalStorage


Install dependencies:

npm install


Start the development server:

npm start


The application will run on:

http://localhost:3000

🧠 How It Works

The application uses React’s useState hook to manage tasks.

Each task is stored as an object in an array. The app:

Saves tasks in localStorage

Loads tasks from localStorage on initial render

Uses map() to render tasks

Uses filter() to delete tasks

Uses conditional rendering to switch between Add and Edit modes

This ensures predictable state updates and persistent user data.

🌐 Deployment

The project is deployed using Vercel with automatic builds connected to the GitHub repository.

Any new push to the main branch triggers a production deployment automatically.

📈 Future Improvements

Mark tasks as completed

Filter tasks (All / Active / Completed)

Add due dates

Add dark mode

Refactor into reusable components

Improve UI/UX styling

📄 License

This project is open source and available under the MIT License.
