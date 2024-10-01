

# Marvel Starter - A Marvel Character and Comics Explorer

Marvel Starter is a simple web application that allows you to explore and learn more about Marvel characters and comics. The application fetches data directly from the Marvel API and presents it in a clean, user-friendly format.

It is built using:

- **React**
- **Marvel API**
- **SCSS** 
- **React Router**

## 👾 Features

- Search for any Marvel character and view detailed information.
- Explore Marvel comics with descriptions, pages, language, and pricing details.
- Fully responsive design optimized for desktop and mobile.
- Error handling for API issues and loading states with spinners.
- Data fetched in real-time from the Marvel API.


## 🚀 Demo

[Marvel Starter Demo](https://eugenyush.github.io/marvel_starter/)


## 📒 Process

I started by implementing the basic structure of the application with React and connected it to the Marvel API. The next step was to create the components for displaying character and comic data, followed by adding routes using React Router.

Once the basic functionality was working, I focused on styling the application using SCSS to ensure a clean and responsive design.

Subsequent improvements included error handling (with spinners and error messages) and performance optimizations such as reducing unnecessary re-renders and improving data-fetching strategies.

Everything is displayed using the data provided by the Marvel API, so users can access the latest information in real-time.

**NOTE:** The purpose of this project is to demonstrate usage of the Marvel API with React. It is not meant to be a complete Marvel fan application.

## 🚦 Running the Project

To run the project in your local environment, follow these steps:

1. **Clone the repository to your local machine**:
   
   ```bash
   git clone https://github.com/eugenyush/marvel_starter.git
   cd marvel_starter
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory and add your Marvel API key:

   ```bash
   REACT_APP_MARVEL_API_KEY=your_marvel_api_key_here
   ```

4. **Start the project**:

   ```bash
   npm start
   ```

   The app will run on [http://localhost:3000](http://localhost:3000) (or the address shown in your console).

## 📹 Video

https://github.com/user-attachments/assets/c0fdfc8b-11e4-4b41-9e03-c5a26c034981


