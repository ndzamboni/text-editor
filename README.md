# Just Another Text Editor (J.A.T.E)

![License](https://img.shields.io/badge/license-MIT-green)
![Issues](https://img.shields.io/github/issues/ndzamboni/text-editor)
![Forks](https://img.shields.io/github/forks/ndzamboni/text-editor)
![Stars](https://img.shields.io/github/stars/ndzamboni/text-editor)
![Contributors](https://img.shields.io/github/contributors/ndzamboni/text-editor)

## Description

Just Another Text Editor (J.A.T.E) is a Progressive Web Application (PWA) that enables users to create and store notes or code snippets directly in their web browser, with the added benefit of offline functionality. The application utilizes data persistence through IndexedDB to ensure that content is stored and retrieved even when the user is offline. Additionally, J.A.T.E can be installed as a PWA, giving users a native app-like experience.

## Installation

Follow these steps to install and run the application locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ndzamboni/text-editor.git
   cd text-editor/Develop
   ```

2. **Install Dependencies**:
    ```
    npm install
    ```

3. **Build the Client**:
    ```
    cd client
    npm run build
    ```

4. **Start the Server**:
    ```
    cd ..
    npm run start
    ```

## Usage

1. **Access the application**:
    ```http://localhost:3000```

2. **Create and save notes**:
* Enter content into the text editor.
* Your content will automatically be saved to IndexedDB when you click outside the editor or close the browser window.

3. **Install the PWA**:
* Click the "Install" button to install the application as a PWA on your desktop.

4. **Use Offline**:
* The application can be used offline, and your data will be saved and retrieved using IndexedDB.

## Features

- **Offline Access**: J.A.T.E works offline, utilizing IndexedDB for storing and retrieving your notes or code snippets, ensuring you can continue working without an internet connection.
- **Installable PWA**: The application can be installed on your desktop as a Progressive Web App (PWA), giving you a native app-like experience.
- **Service Worker Integration**: Pre-caches resources, allowing for faster load times and offline functionality.
- **Modern JavaScript**: The application leverages next-gen JavaScript features and is compiled using Babel to ensure compatibility across various browsers.
- **Webpack Bundling**: Efficiently bundles JavaScript, CSS, and other assets for optimized performance.

## Technologies Used

- **Node.js**: JavaScript runtime environment that powers the server-side logic.
- **Express.js**: Lightweight web application framework for Node.js, used to create the backend server.
- **Webpack**: Module bundler that compiles JavaScript files along with assets like images, fonts, and stylesheets.
- **Babel**: JavaScript compiler that enables the use of modern JavaScript syntax across different browsers.
- **IndexedDB**: Client-side storage mechanism for saving significant amounts of structured data in the browser.
- **idb**: A simple and easy-to-use wrapper for IndexedDB, making it more accessible to developers.
- **Service Worker**: A script that your browser runs in the background, enabling features like offline caching and push notifications.
- **Workbox**: A set of libraries and Node modules that simplify common service worker tasks, such as caching assets and managing fetch requests.
- **PWA (Progressive Web App)**: A type of application that is delivered through the web, providing native app-like functionality, including offline capabilities and installation.

## Deployment

The application can be deployed on any cloud platform that supports Node.js, such as Render, Heroku, or Vercel.

### Example Deployment on Render

1. **Sign up for a Render account**: If you don't have an account, create one at [Render](https://render.com/).

2. **Deploy the application**:
   - Create a new web service on Render.
   - Connect your GitHub repository where the project is stored.
   - Set the root directory to `Develop`.
   - Specify the build command as `npm install && npm run build`.
   - Set the start command to `npm run start`.
   - Deploy your application and Render will handle the rest.

## License

This project is licensed under the MIT License. You can view the full license in the [LICENSE](LICENSE) file included with this repository.

## Contributing

Contributions are welcome! To contribute to this project, follow these steps:

1. **Fork the repository** on GitHub.
2. **Create a new feature branch**:
   ```bash
   git checkout -b feature/YourFeature

## Commit your changes

3. **Commit your changes**:
   ```bash
   git commit -m 'Add some feature'

## Push to the branch

4. **Push to the branch**:
   ```bash
   git push origin feature/YourFeature

## Open a pull request

5. **Open a pull request**:
   - Navigate to your forked repository on GitHub.
   - Click on the "Pull requests" tab.
   - Click on the "New pull request" button.
   - Select the branch you just pushed.
   - Review the changes you’ve made, and provide a clear and concise description of the feature or fix you’re proposing.
   - Submit the pull request, and wait for it to be reviewed.

## Questions

If you have any questions or encounter any issues, feel free to open an issue in this repository. You can also reach out to me via email at your-email@example.com. For more projects and contributions, visit my GitHub profile at [ndzamboni](https://github.com/ndzamboni).
