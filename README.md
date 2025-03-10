# Desktop Companion

[![License](https://img.shields.io/badge/license-ISC-blue.svg)](https://opensource.org/licenses/ISC)

Desktop Companion is a simple Electron-based desktop application designed to provide a fullscreen, interactive experience. This application serves as a foundation for building customizable desktop utilities or information dashboards.

## Features
- Built with **Electron.js** for cross-platform compatibility
- Fullscreen mode for an immersive user experience
- Custom renderer script for UI interactions
- Easy to set up and run

## Installation
### Prerequisites
Make sure you have **Node.js** installed on your system. You can download it from [nodejs.org](https://nodejs.org/).

### Clone the Repository
```sh
git clone https://github.com/AnoniMono/Desktop-Companion.git
cd Desktop-Companion
```

### Install Dependencies
```sh
npm install
```

## Usage
To start the application, run:
```sh
npm start
```

This will launch the Electron app in fullscreen mode.

## Project Structure
```
Desktop-Companion/
├── node_modules/
├── src/
│   ├── main.js        # Electron main process
│   ├── renderer.js    # Renderer script for UI interactions
│   ├── index.html     # HTML UI (not included in current repo, needs to be added)
├── package.json       # Project configuration
├── package-lock.json  # Dependency lock file
├── README.md          # Documentation
```

## Troubleshooting
- **App fails to launch?** Ensure the `src` folder exists and contains `main.js`.
- **Incorrect folder name issue?** If the folder is named `scr`, rename it to `src`.
- **Dependencies missing?** Run `npm install` to install the required modules.

## License
This project is licensed under the **ISC License**. See the `LICENSE` file for details.

## Contribution
Feel free to fork this repository and submit pull requests for improvements or bug fixes.

---
**Author:** [AnoniMono](https://github.com/AnoniMono)

