# TMDB CLI TOOL

A simple command line tool to search for movies in The Movie Database (TMDB).

## Features

- Search movies by category:
  - **Now Playing**
  - **Popular**
  -  **Top Rated**
  -  **Upcoming**
- Handles errors related to connection or API.

## Prerequisites:

- **Nodejs** installed
- A valid **token** authentication from TMDB

## Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/nick-0037/tmdb-cli-tool.git
  cd tmdb-app
  ```

2. Install dependecies:
  ```bash
  npm install
  ```

3. Run the application:
 
    - **First method**:
      
    ```js
    node todo-app --type playing  // - Categories: (plyaing, top, popular, upcoming)
    ```

    - **Second method**:
      
    ```js
    npm link // It creates a global symbolic link, registering tmdb-app as a command accessible from any terminal.
    todo-app --type top
    ```
