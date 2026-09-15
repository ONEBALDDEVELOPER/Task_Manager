# Task Manager

A minimal to-do list built with plain HTML, CSS, and JavaScript. No build step, no dependencies, no server — just open it in a browser.

## Features

- Add a task via the input field
- Delete a task from the list
- Clean, responsive card-based UI

Tasks live only in memory — refreshing the page clears the list, since there's no persistence layer yet.

## Getting Started

Clone the repo and open `index.html` directly in your browser:

```bash
git clone https://github.com/yourusername/task_manager.git
cd task_manager
open index.html   # or just double-click the file
```

## Usage

1. Type a task into the input field.
2. Click **Add Task** to add it to the list.
3. Click **Delete** on any task to remove it.

Note: pressing Enter in the input field does not submit — use the **Add Task** button.

## Project Structure

```
Task_Manager/
├── index.html      # Markup
├── style.css       # Styling
├── script.js       # App logic
└── README.md       # This file
```

## Roadmap

Ideas for future improvements:

- [ ] Persist tasks with `localStorage`
- [ ] Mark tasks as complete
- [ ] Edit existing tasks
- [ ] Submit new tasks with Enter
