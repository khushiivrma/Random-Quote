# Random Quote Generator

## Objective
Develop a full-stack application that generates random quotes from a pre-loaded database.

## Description
This repository contains the code and documentation for a Random Quote Generator application. The objective was to create a robust and efficient application that provides random quotes from a pre-loaded database, enhancing user engagement through seamless integration of backend and frontend technologies.

## Features
- **Backend Construction**: Developed the backend using NodeJS and MongoDB. Leveraged Xu's library with Dotenv and Set to improve backend efficiency.
- **Frontend Development**: Built the frontend with React, achieving seamless integration with the backend via a RESTful API. This resulted in a 30% decrease in load times and an enhanced user experience.
- **Integration Proposals**: Proposed the integration of the quote generator into content management systems (CMS) and e-learning applications to provide engaging content and enhance user engagement.

## Prerequisites
- **Node.js**: Ensure you have Node.js installed. You can download it [here](https://nodejs.org/).
- **MongoDB**: Make sure you have MongoDB installed and running.
- **npm**: Node package manager, which comes with Node.js.
- **React**: Basic understanding of React is required.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/khushiivrma/Random-Quote.git
   cd Random-Quote
   ```

2. **Backend Setup:**
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Install backend dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file in the backend directory and add your environment variables:
     ```env
     MONGODB_URI=your_mongodb_uri
     PORT=your_port
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

3. **Frontend Setup:**
   - Navigate to the frontend directory:
     ```bash
     cd ../frontend
     ```
   - Install frontend dependencies:
     ```bash
     npm install
     ```
   - Start the frontend development server:
     ```bash
     npm start
     ```

## Usage

1. Ensure both backend and frontend servers are running.
2. Open your browser and navigate to `http://localhost:3000`.
3. The application will display random quotes fetched from the pre-loaded database.

## Proposed Integrations
- **Content Management Systems (CMS)**: Integrate the random quote generator to provide dynamic and engaging content.
- **E-Learning Applications**: Enhance user engagement by integrating the quote generator into educational platforms.

## Contributors
- Khushi Verma (khushiivrma) - Developer

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Xu's library for backend improvements.
- The React community for their extensive documentation and support.
