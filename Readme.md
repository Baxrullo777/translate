# Translate

## Project Description

Translate is a full-stack application designed to provide real-time translation services between multiple languages. This project leverages modern web technologies to deliver a seamless user experience for translating text and web pages without the need for user registration.

## Features

- Real-time text translation between multiple languages
- Simple and intuitive user interface
- Language selection for source and target languages
- No user registration required

## Technologies Used

### Front-end

- React.js: For building a dynamic and responsive user interface
 

### Back-end

- Node.js: Server-side JavaScript runtime
- Express.js: Web framework for Node.js
- Google Cloud Translation API: For the actual translation services

## Installation Instructions

### Prerequisites

- Node.js and npm installed
- Google Cloud Translation API key

### Steps

1. Clone the repository:

  
   git clone https://github.com/Baxrullo777/translate
   cd translate
   
2. Install dependencies:

  
 # cd translate frontend
   npm install
 
 # cd translate backend
   npm install
   
3. Set up environment variables:

   Create a .env file in the root directory and add your Google Cloud Translation API key:

  
   GOOGLE_API_KEY=your_google_api_key
   
4. Run the application:

  
   npm run dev
   

## Usage

1. Open your browser and navigate to:

  
   http://localhost:5173   
2. Start translating:

   - Enter the text you want to translate.
   - Select the source and target languages from the dropdown menus.
   - Click the "Translate" button to get the translation.

  

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

 