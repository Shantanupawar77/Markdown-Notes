# Markdown Notes

Markdown Notes is a React application that allows users to create, edit, and store notes in markdown format. The application features a split view with a sidebar for navigation and an editor for note content.


## Features

- Create new notes
- Edit notes with a markdown editor
- Store notes in local storage
- Split view for easy navigation and editing
- Toggle between write and preview modes

## Components

1. **App**: Main container component that manages state and renders `Sidebar` and `Editor`.
2. **Sidebar**: Displays a list of notes and allows creating new notes.
3. **Editor**: Provides a markdown editor for editing the content of the selected note.

## How to Use

To use this project:

1. Clone this repository to your local machine using `git clone <repository-url>`.
2. Navigate to the project directory: `cd Markdown-Notes`.
3. Install the dependencies by running `npm install`.
4. Start the development server by running `npm start`.
5. Open your browser and go to `http://localhost:3000` to view the application.

## Code Overview

### App Component

Manages the state for notes and the current note ID. Handles creating new notes, updating notes, and persisting notes in local storage.

### Sidebar Component

Displays a list of notes and allows users to select a note to edit or create a new note.

### Editor Component

Provides a markdown editor for editing the content of the selected note. Uses `ReactMde` and `Showdown` for markdown support.

## Styles

The project uses CSS for styling, with classes to handle the layout and appearance of the components.

## Author

- [Shantanu Pawar](https://github.com/Shantanupawar77)

Feel free to contribute to this project by submitting issues or pull requests.
