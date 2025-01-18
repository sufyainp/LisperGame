# Random Secrets Viewer

Random Secrets Viewer is a simple Node.js application built using Express.js. It fetches random secrets and usernames from an external API and displays them dynamically on a webpage using the EJS templating engine.

## Features:
- **API Integration**: Fetches data from the [Secrets API](https://secrets-api.appbrewery.com/random).
- **Dynamic Content Rendering**: Displays the secret and associated username dynamically on a web page.
- **Static File Serving**: Hosts static files in the `public` directory.
- **Error Handling**: Logs errors and returns a 500 status code in case of API failures.

## Tech Stack:
- **Backend**: Node.js with Express.js
- **Frontend**: EJS templates
- **HTTP Requests**: Axios

## How to Run:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd random-secrets-viewer
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   node app.js
   ```
4. Visit `http://localhost:3000` in your browser to view random secrets.

Feel free to fork and modify the project!
