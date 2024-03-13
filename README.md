# Simple HTML Template

## Description

This project is a basic template for a website. It employs HTML, CSS, and JavaScript to create a simple yet extendable skeleton for web development. The project's architecture is designed to be intuitive and easy to customize.

## Project Structure

Here's the layout of the project:

- `index.html`: The main page of the site.
- `css/`: Folder containing the CSS files.
    - `reset.css`: Resets default browser styles for consistency across browsers.
    - `style.css`: Contains custom styles for the site.
- `js/`: Folder containing the JavaScript scripts.
    - `app.js`: The main JavaScript file for the site's functionality.
- `images/`: Folder containing the Images files.

## Using Reset CSS

This project uses Meyerweb's [reset.css](https://meyerweb.com/eric/tools/css/reset/) to reset the default styles of browsers, ensuring consistency across different browsers and providing a better foundation for custom styles.

## Cloning the Project

To use this project, you need to clone the repository from GitHub. Here are the steps to do so:

1. **Open the terminal.** If you're using Windows, you can use Git Bash or the Command Prompt.

2. **Clone the repository.** Use the following command:
    ```
    git clone git@github.com:LeZellus/simple-html-template.git
    ```

3. **Navigate to the project folder.** After cloning, use:
    ```
    cd ProjectName
    ```

4. **Explore the files.** You can now open the files in your favorite code editor.

## Node-Sass Installation and Setup

To use `node-sass` for automatically compiling your SCSS/SASS files, you need to have Node.js installed and set up on your system. Here’s how you can do it:

### Step 1: Install Node.js

First, install Node.js from [Node.js official website](https://nodejs.org/). Download and run the installer for your operating system.

### Step 2: Initialize npm in Your Project

Navigate to your project directory in the command line and run the following command to initialize npm. This will create a `package.json` file in your project.

```bash
npm init
```

### Step 3: Install node-sass

Now, install node-sass in your project as a dev dependency. This tool will help you to compile your SCSS/SASS files into CSS.

```bash
npm install node-sass --save-dev
```

### Step 4: Set Up Script for Compilation

In your package.json file, set up a script to compile your SCSS/SASS files. Edit the following line to the scripts section according to your project (it works in state):

```bash
"scripts": {
  "sass": "node-sass -w scss/ -o css/ --recursive"
}
```

### Step 5: Run the Compiler

To start the compilation process, run the following command in your terminal:

```bash
npm run sass
```

## Contributing

Contributions to this project are welcome. If you wish to contribute, please follow these steps:

1. **Fork the project.** This will create a copy of the project on your GitHub account.

2. **Create a new branch.** This allows you to work on a new feature without affecting the main branch.

3. **Make your changes and commit them.**

4. **Submit a Pull Request.** Please clearly explain the changes made and their purpose.