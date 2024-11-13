# Front-end (Fiona)
Here is a step-by-step documentation for the Front End part of the project. Here is an overview of how the file structure looks like:

```
src
├── assets
│   └── logo.svg
├── components
│   ├── FoodForm
│   │   ├── FoodForm.js
│   │   ├── FoodForm.css
│   │   └── FoodForm.test.js
│   └── FoodList
│       ├── FoodList.js
│       ├── FoodList.css
│       └── FoodList.test.js
├── services
│   └── apiService.js
├── styles
│   ├── App.css
│   └── index.css
├── utils
├── App.js
├── App.test.js
├── index.js
├── reportWebVitals.js
└── setupTests.js
```

### **Step 1: Set Up the Project Environment**

Here is the steps I took to start a server and start working on the FrontEnd part of the project.

1. **Clone the Repository**

   - Clone the project repository from version control.
   - Navigate to the frontend directory:
     ```bash
     cd NutriTrackReactApp/.../NutriTrackClient
     ```
2. **Install Dependencies**

   - Install all required dependencies for the React project:
     ```bash
     npm install
     ```
3. **Start the Application**

   - Run the application to make sure everything is set up correctly:
     ```bash
     npm start
     ```
   - The app should be available at `http://localhost:3000`. Check if it’s running without any errors.
