# ScriptScribe: Offline Text Editor PWA

ScriptScribe is a robust offline text editor progressive web application (PWA) designed to facilitate seamless note-taking and code snippet creation, even in environments with limited or no internet connectivity. Built with modern web technologies, ScriptScribe empowers users to create, edit, and store text content reliably, ensuring accessibility and usability across various devices and platforms.

## Features

### Offline Functionality
ScriptScribe offers uninterrupted text editing capabilities, allowing users to compose and modify content without relying on an active internet connection. By leveraging client-side data storage and synchronization techniques, ScriptScribe ensures that users can work on their text documents anytime, anywhere.

### IndexedDB Integration
To enable persistent data storage, ScriptScribe utilizes IndexedDB, a low-level API for client-side storage of significant amounts of structured data. Through IndexedDB integration, ScriptScribe securely stores user-generated content locally, providing a seamless experience for saving and retrieving text documents across sessions.

### Progressive Web App (PWA) Features
As a progressive web application, ScriptScribe delivers an enhanced user experience reminiscent of native desktop and mobile applications. With features such as a web app manifest and service worker, ScriptScribe offers installability, offline access, and smooth performance, enabling users to add the app to their device home screens and enjoy a seamless, app-like experience.

### Lightweight and Intuitive Interface
ScriptScribe prioritizes simplicity and ease of use, offering a clean and intuitive interface for text editing tasks. The application's minimalist design and straightforward functionality make it accessible to users of all skill levels, from casual note-takers to seasoned developers.

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine

### Installation
1. Clone the repository:
git clone <git@github.com:bchris240/ScriptScribe.git>

2. Navigate to the project directory:
cd ScriptScribe

3. Install dependencies:
npm install

### Usage
1. Build the project:
npm run build

2. Start the server:
npm start

3. Open your preferred web browser and navigate to `http://localhost:3000` to access the application.

## Technologies Used

- Node.js
- Express.js
- IndexedDB
- Workbox (for service worker)
- Webpack

## Contributing

Contributions to ScriptScribe are welcome and encouraged! If you have ideas for improvements, new features, bug fixes, or other enhancements, please feel free to open an issue or submit a pull request. For major changes, please discuss them first by creating an issue to communicate with the project maintainers.

