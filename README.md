# Markdown Previewer

This project is a Markdown Previewer built with React. It allows users to write Markdown in an editor and see a live preview of the rendered Markdown. The app includes features such as formatting options, word and character count, theme toggle, and the ability to save, load, and download Markdown content.

## Features

- **Editor**: Write Markdown and see a live preview.
- **Formatting**: Apply formatting options such as bold, italic, and headers using the toolbar.
- **Markdown Preview**: Real-time rendering of Markdown with support for various Markdown syntax elements.
- **Word and Character Count**: Display the number of words and characters in the Markdown text.
- **Theme Toggle**: Switch between light and dark mode for better readability.
- **View Modes**: Toggle between split view (editor and preview side-by-side) and live preview mode.
- **Local Storage**: Save and load Markdown content from local storage.
- **Download as File**: Download the Markdown content as a `.md` file.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/markdown-previewer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd markdown-previewer
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the development server:
   ```bash
   npm start
   ```
2. Open your browser and go to `http://localhost:3000` to view the app.

## Components

### `App.js`

- **State Management**: Manages the state for Markdown content, view mode, and theme mode.
- **Handlers**: 
  - Toggle view mode between split view and live preview.
  - Toggle theme between dark mode and light mode.
  - Save and load Markdown from local storage.
  - Download the Markdown content as a file.

### `Editor.js`

- **Markdown Input**: A textarea where users can write or paste their Markdown content.
- **Formatting**: Provides functions to format the selected text as bold, italic, or header using a toolbar.

### `Preview.js`

- **Markdown Rendering**: Uses the `marked` library to render Markdown content as HTML.

### `MarkdownStats.js`

- **Word and Character Count**: Displays the number of words and characters in the Markdown content.

### `Toolbar.js`

- **Formatting Toolbar**: A set of buttons to apply Markdown formatting to selected text.

## Styling

- The app is styled using CSS, with support for both dark and light themes.

## Future Enhancements

- Add more formatting options like code blocks, links, and images.
- Implement drag-and-drop support for uploading Markdown files.
- Add a mobile-responsive design for smaller screens.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
