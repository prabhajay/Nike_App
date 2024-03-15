# Nike App:
### 1. Create your project
Start by creating a new React project with Create React App v5.0+ if you don't have one already set up.
    
    npx create-react-app my-project
    cd my-project

### 2.Install Tailwind CSS
Install tailwindcss via npm, and then run the init command to generate your tailwind.config.js file.

    npm install -D tailwindcss
    npx tailwindcss init

### 3.Configure your template paths
Add the paths to all of your template files in your tailwind.config.js file.

    /** @type {import('tailwindcss').Config} */
    module.exports = {
    content: [
    "./src/**/*.{js,jsx,ts,tsx}",
    ],
    theme: {
    extend: {},
    },
    plugins: [],
    }

### 4.Add the Tailwind directives to your CSS
Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

