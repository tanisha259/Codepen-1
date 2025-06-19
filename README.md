
🖊️ CodePen Clone

A CodePen-like clone built using React.js, designed to allow users to write and preview HTML, CSS, and JavaScript code live in the browser. This project is ideal for learning and practicing web development in a live environment.


🚀 Features

Live HTML, CSS, and JS code editor with preview

Responsive design

Syntax highlighting using CodeMirror

Separate panels for each code type

Real-time rendering in iframe

React-based architecture



---

🛠️ Tech Stack

Frontend: React, HTML, CSS, JavaScript

Packages Used:

react-codemirror2

@fortawesome/react-fontawesome

@fortawesome/free-solid-svg-icons

classnames




---

⚙️ Installation & Running Locally

1. Clone the repository

git clone https://github.com/tanisha259/Codepen-1.git

cd codepen-clone

2. Install dependencies

npm install

3. Fix Node.js compatibility issue

If you're using Node.js v17 or higher (e.g. v22), add this to your package.json:

"scripts": {
  "start": "set NODE_OPTIONS=--openssl-legacy-provider && react-scripts start"
}

Or for Mac/Linux:

"start": "NODE_OPTIONS=--openssl-legacy-provider react-scripts start"

Also, make sure .eslintignore exists and contains:

node_modules/

4. Start the app

npm start

The app will run at http://localhost:3000 or the port you’ve set.


---

📁 Project Structure

src/
│
├── components/     # Editor components
├── App.js          # Main app logic
├── index.js        # ReactDOM entry
├── styles/         # Custom CSS
└── ...


---

🐞 Troubleshooting

Problem: no-unused-expressions in node_modules

✅ Add .eslintignore file with: node_modules/

✅ Or disable ESLint temporarily by adding --no-eslint to start script


Problem: digital envelope routines::unsupported

✅ Add --openssl-legacy-provider to NODE_OPTIONS

✅ Or downgrade Node.js to v16 or v18 LTS



---

✨ Future Improvements

Add login and user sessions

Save code to cloud (e.g., Firebase)

Shareable code snippets

Dark mode


🙌 Acknowledgements

Inspired by CodePen

Built with ❤️ using React

