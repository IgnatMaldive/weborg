# WebOrg

A fast, web-based emulator of Emacs Org-mode using WebGL.

https://ignatmaldive.github.io/weborg/

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Screenshot](#screenshot)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

**WebOrg** is a single HTML file that simulates a basic Emacs Org-mode text editing experience using WebGL. It serves as a simple note-taking and editing tool with basic Org-mode syntax highlighting. The editor supports headings and list items, and you can interact with it using your keyboard.

## Features .

- **WebGL Rendering:** Utilizes WebGL for canvas initialization and clearing, while text rendering is handled via the 2D context for simplicity.
- **Basic Org-Mode Syntax Highlighting:**
  - **Headings:** Lines starting with `*` are displayed in blue.
  - **List Items:** Lines starting with `-` are displayed in green.
- **Cursor Navigation:** Supports arrow keys for moving the cursor up, down, left, and right.
- **Text Editing:** Allows character insertion, backspace deletion, and creating new lines.

## Screenshot

![WebOrg Screenshot](image.jpg)

*Note: Replace `screenshot.png` with the actual path to your screenshot image.*

## Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/username/WebOrg.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd WebOrg
   ```

3. **Open the HTML file:**

   - Open `index.html` in your preferred web browser.

## Usage

1. **Launch the Editor:**

   - Open `index.html` in your web browser.

2. **Interact with the Editor:**

   - Click anywhere on the canvas to focus.
   - Use your keyboard to type text.
   - Navigate using the arrow keys.
   - Use **Backspace** to delete characters.
   - Press **Enter** to create new lines.

3. **Org-Mode Syntax Highlighting:**

   - **Headings:** Start a line with `*` to create a heading (displayed in blue).
   - **List Items:** Start a line with `-` to create a list item (displayed in green).

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add your feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeature
   ```

5. Open a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Emacs Org-mode](https://orgmode.org/) for the inspiration.
- [WebGL](https://www.khronos.org/webgl/) for rendering capabilities.
- Thanks to all contributors!