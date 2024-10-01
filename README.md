
# Marvel Starter Project

## 📖 Overview

The **Marvel Starter** project is a React-based web application that allows users to explore Marvel characters, comics, and related data. The app utilizes the Marvel API to fetch detailed information about each character and comic, and provides a user-friendly interface for navigation.

## ✨ Features

- **Marvel Character Search**: Search for detailed information about any Marvel character.
- **Comics Library**: Browse through a collection of comics with detailed descriptions, pages, language, and prices.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Error Handling**: Robust error messages and loading states for improved user experience.

## 🚀 Demo

[Marvel Starter Demo](https://eugenyush.github.io/marvel_starter/)

## 📦 Installation

### Prerequisites

- **Node.js**: Ensure you have Node.js installed on your machine. You can download it [here](https://nodejs.org/).
- **Marvel API Key**: To fetch data from the Marvel API, you will need an API key. You can obtain one by signing up [here](https://developer.marvel.com/).

### Step-by-Step Guide

1. **Clone the repository**:

   \`\`\`bash
   git clone https://github.com/eugenyush/marvel_starter.git
   cd marvel_starter
   \`\`\`

2. **Install dependencies**:

   Run the following command to install all required dependencies:

   \`\`\`bash
   npm install
   \`\`\`

3. **Set up environment variables**:

   Create a `.env` file in the root of the project and add your Marvel API key:

   \`\`\`bash
   REACT_APP_MARVEL_API_KEY=your_marvel_api_key_here
   \`\`\`

4. **Start the development server**:

   \`\`\`bash
   npm start
   \`\`\`

   This will launch the application in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 📂 Project Structure

\`\`\`bash
marvel_starter/
├── public/                # Public assets
├── src/
│   ├── components/        # Reusable components
│   ├── pages/             # Pages like Character, Comic, etc.
│   ├── services/          # API service to fetch data from Marvel API
│   ├── styles/            # Global styles and SCSS files
│   └── App.js             # Main App component
├── .env                   # Environment variables (Marvel API key)
├── package.json           # Project dependencies and scripts
└── README.md              # Project documentation
\`\`\`

## 🔧 Technologies Used

- **React**: JavaScript library for building user interfaces.
- **React Router**: Library for routing in React applications.
- **Marvel API**: External API to fetch data about characters and comics.
- **SCSS**: Preprocessor for styling.

## ⚙️ API Integration

The application interacts with the Marvel API to fetch data about characters and comics. The following services are used:

- **\`getCharacterById\`**: Fetches a character by its unique ID.
- **\`getComics\`**: Retrieves comics data.
- **\`clearError\`**: Resets any previous API errors before making a new request.

### Example API Call

To fetch a character by ID:

\`\`\`js
import useMarvelService from '../../services/MarvelService';

const { getCharacterById } = useMarvelService();

getCharacterById(characterId).then(character => {
  console.log(character);
});
\`\`\`

## 🛠️ Available Scripts

In the project directory, you can run:

- **\`npm start\`**: Runs the app in the development mode.
- **\`npm test\`**: Launches the test runner.
- **\`npm run build\`**: Builds the app for production to the \`build\` folder.

## 🐞 Error Handling

The app provides meaningful error messages if API requests fail. Both loading states and error components ensure a smooth user experience even if data cannot be fetched.

- **\`ErrorMessage\` Component**: Displays when something goes wrong while fetching data.
- **\`Spinner\` Component**: Displays a loading spinner when data is being fetched.

## 🚧 Future Enhancements

Some ideas for future development:

- **Pagination**: Add pagination to the character and comic lists.
- **Favorite Characters**: Allow users to favorite and save their preferred characters.
- **More Marvel Data**: Expand the app to include more categories like series, events, and stories.

## 📞 Contact

For any questions or feedback, feel free to contact the project maintainer:

- **GitHub**: [eugenyush](https://github.com/eugenyush)
