# Email Writer Assistance

## Overview
Email Writer Assistance is an AI-powered tool that generates email replies using Google's Gemini AI. The project consists of a backend built with Java (Spring Boot), a React-based web application, and a browser extension that integrates the AI-generated responses directly into the email compose window.

## Features
- AI-generated email replies using Gemini AI
- Web application for composing and refining AI-generated emails
- Browser extension that adds an AI button in the email compose window
- REST API backend using Java and Spring Boot

## Tech Stack
- **Backend**: Java (Spring Boot)
- **Frontend**: React
- **AI Model**: Gemini
- **Browser Extension**: JavaScript

## Installation

### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Email-Writer-Assistance.git
   ```
2. Navigate to the backend directory:
   ```sh
   cd email-writer-sb
   ```
3. Build the project:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd email-writer-react
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

### Browser Extension Setup
1. Navigate to the extension directory:
   ```sh
   cd email-writer-extension
   ```
2. Load the extension in Chrome:
   - Open `chrome://extensions/`
   - Enable Developer Mode
   - Click "Load unpacked" and select the `email-writer-extension` directory

## Usage
1. Open the web application.
2. Enter an email or response prompt.
3. Click "Generate Reply" to receive AI-generated suggestions.
4. Use the browser extension to integrate AI responses directly into your email compose window.

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License.


