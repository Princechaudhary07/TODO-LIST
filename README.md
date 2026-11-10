# TODO List

A simple and responsive to-do list web app built with HTML, CSS, and JavaScript.

## Features

- Add new tasks
- Mark tasks as completed
- Remove tasks
- Persist tasks in the browser using `localStorage`
- Clean, modern UI with gradient styling

## Project Structure

- `index.html` — app layout
- `style.css` — styling and responsive design
- `script.js` — task logic and storage behavior
- `images/` — icons used for the app

## How to Run

You can run the project by opening `index.html` directly in a browser.

For a local preview server, use:


## How It Works

- Enter a task in the input box and click **Add**.
- Click a task to toggle it as completed.
- Click the `×` button next to a task to delete it.
- Tasks remain saved in the browser after refresh because they are stored in `localStorage`.

## Files Overview

### `script.js`

Contains the main logic for:

- creating tasks
- toggling completed state
- deleting tasks
- saving and restoring tasks from browser storage

### `style.css`

Defines the layout, colors, button styling, list item states, and checked/unchecked indicators.
