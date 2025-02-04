# Todo List Application

A simple, responsive todo list application built with HTML, CSS, and JavaScript. This application allows users to add, complete, and delete tasks, with data persistence using localStorage.

## Features

- Add new tasks
- Mark tasks as complete/incomplete
- Delete tasks
- Responsive design for mobile and desktop
- Data persistence using localStorage
- Clean and modern user interface

## Getting Started

### Running Locally

1. Clone this repository or download the files
2. Open `index.html` in your web browser
3. Start adding your todos!

### Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin YOUR_REPOSITORY_URL
   git push -u origin main
   ```
3. Go to your repository's Settings
4. Scroll down to the "GitHub Pages" section
5. Under "Source", select "main" branch
6. Click "Save"
7. Your site will be published at `https://YOUR_USERNAME.github.io/REPOSITORY_NAME`

## Technical Details

### Structure
- Single HTML file containing all necessary CSS and JavaScript
- Uses ES6+ features
- Implements class-based architecture
- Responsive design using CSS media queries

### Data Storage
- Uses localStorage for data persistence
- Data structure:
  ```javascript
  {
    id: number,
    text: string,
    completed: boolean
  }
  ```

### Browser Support
- Works on all modern browsers
- Requires ES6+ support

## Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## License

This project is licensed under the MIT License - see the LICENSE file for details.# todo-list-app
