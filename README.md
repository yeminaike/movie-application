  
<h4>
    <a href="https://tmovies-blush.vercel.app/">View Demo Here</a>

<br/>
<br/>

## Features

1. **Search Movies and TV Series:**

   1. Users can easily search for their favorite movies and TV series within the application.
   2. View trailers to get a sneak peek before watching.

2. **Detailed Movie Information:**

   1. Access comprehensive information about a selected movie, including details about the cast, crew, and more.

<br/>





<br/>
<br/>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

\***\* Prerequisites \*\***

- git
  If you want to clone the project from GitHub and work with it locally, you will need to have Git installed on your system. You can download and install Git from the official website (**[https://git-scm.com/](https://git-scm.com/)**).
- Node.js
  Application requires Node.js to be installed on your system in order to run. You can download and install the latest version of Node.js from the official website (**[https://nodejs.org/](https://nodejs.org/)**).
- npm (Node Package Manager)
  npm is the package manager for Node.js, and is used to manage the dependencies and packages required for your Next.js project. It is installed automatically when you install Node.js.
  To check if npm is installed on your system, you can open a terminal or command prompt and enter the following command:
  ```bash
  npm -v
  ```

Once you have these prerequisites in place, you can proceed to clone the project from GitHub using Git.

<br/>

\***\* Installing \*\***

Make sure you have all the necessary prerequisites installed on your system. Follow the below steps to install the setup the project on your machine:

- Open a terminal or command prompt and navigate to the directory where you want to clone the project.
- Run the following command to clone the project from GitHub:
  ```bash
  git clone https://github.com/sudeepmahato16/movie-app.git
  ```
- This will create a new directory called "movie-app" in the current location, containing the code for the movie app project.
- Navigate to the project directory by running the following command:

  ```bash
  cd movie-app
  ```

- Run the following command to install the project's dependencies using npm:

  ```bash
  npm install
  ```

- Start the server

  ```bash
  npm run dev
  ```

- To use the movie project, you will need to set up some environment variables on your development machine. Here are the steps to follow:

  1. Create a **`.env`** file in the root of the project.
  2. Add the following variables to the **`.env`** file, replacing the placeholder values with your own:

  ```jsx
  VITE_API_KEY=<your-tmdb-api-key>
  VITE_TMDB_API_BASE_URL = https://api.themoviedb.org/3
  ```

  3. Save the **`.env`** file.

- Once the dependencies are installed, you can run the project locally by running the following command:
  ```bash
  npm run dev
  ```

This will start the development server and open the movie application in your default web browser.

<br/>

