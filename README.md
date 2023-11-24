# React Sidebar and Modal Project

## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Overview

This React project implements a sidebar and modal layout. It provides a clean and customizable solution for integrating these UI elements into your web applications. The project is built using React and utilizes global context for managing the state of the sidebar and modal components.

## Demo

Check out the live demo [here](https://esmat-sidebar-modal.onrender.com/).

![Demo pic](https://res.cloudinary.com/tawfeer/image/upload/v1700854909/sidebar-modal-project_z9u55q.png)

## Installation

To get started with this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Mohamed-Esmat/sidebar-modal-react.git
   ```

2. Install dependencies:

   ```bash
   cd sidebar-modal-react
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

## Usage

### Explore Data

Navigate to `src/data.jsx` and explore the arrays used in the project.

### Create Components

Three main components are created: `Home`, `Modal`, and `Sidebar`. They are rendered in `src/App.jsx`.

### Global Context

Global context is set up using a custom hook to manage the state of the application.

### Global State Values

Two boolean state values, `isSidebarOpen` and `isModalOpen`, are set up along with four functions to open and close the modal and sidebar.

### Home Component

In the `Home` component, two buttons are set up to invoke functions from the global context (`openSidebar` and `openModal`).

### Modal and Sidebar Component

Separate components are created for the modal and sidebar, each with their respective CSS.

## Components

- **Home**: Main component rendering buttons to trigger sidebar and modal.
- **Modal**: Component rendering a customizable modal.
- **Sidebar**: Component rendering a sidebar with navigation links.

## Customization

The CSS files (`src/App.css` and `src/components/Modal.css`, `src/components/Sidebar.css`) provide a clean and modular structure for easy customization. You can modify the styles to match your project's design.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).
