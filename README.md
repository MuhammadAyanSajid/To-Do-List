# Simple To-Do List

A small, lightweight To-Do List web app built with plain HTML, CSS, and JavaScript. It stores tasks in the browser's localStorage so your todos persist between sessions.

## Features

- Add tasks using the input field and the Add button or press Enter
- Mark tasks complete with a checkbox (visual line-through and saved state)
- Edit tasks by double-clicking the task text
- Delete tasks with the Delete button
- Persistent storage using localStorage
- Responsive layout and simple animations

## Files

- `index.html` — The page structure and markup
- `style.css` — All styling (glassmorphism look, animations, responsive)
- `script.js` — App logic for creating, editing, deleting, and saving todos

## Usage

1. Open `index.html` in a browser (double-click the file or use a local server).
2. Type a todo in the input field and press Add or Enter.
3. Double-click a todo to edit it.
4. Click the checkbox to mark as completed. The state is remembered.
5. Click Delete to remove a todo.

## Run locally (recommended)

You can open `index.html` directly in most browsers. For a slightly better experience and to avoid any local-file restrictions, serve the folder using a simple static server.

Using Python 3 (if installed):

```powershell
cd "c:\Users\User\Documents\To Do List"
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Troubleshooting

- If todos are not saving, ensure your browser allows localStorage for file URLs or serve the site via a local server.
- If JavaScript doesn't run, open the browser devtools console (F12) and check for errors.

## Deploy on GitHub Pages

You can easily deploy this project on GitHub Pages by following these steps:

1. Go to your repository on GitHub (`https://github.com/MuhammadAyanSajid/To-Do-List`)
2. Click on "Settings" (top navigation bar)
3. Scroll down to "GitHub Pages" section
4. Under "Source", select "GitHub Actions"
5. The workflow I've already set up (`.github/workflows/deploy.yml`) will automatically deploy your site when you push to the `main` branch
6. After a few minutes, your site will be live at: `https://muhammadayansajid.github.io/To-Do-List/`

Your site should be updated automatically whenever you push changes to the `main` branch.

## License

This project is provided as-is under the MIT License. Feel free to use and modify.

## Contributing

Small improvements (styling tweaks, accessibility, tests) are welcome. Open an issue or PR on the GitHub repository.

---

Created and documented on October 18, 2025.
