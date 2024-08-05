# Blog Frontend

## Introduction

This project is the frontend for a blog website, built using React. It communicates with the backend to handle user authentication, blog post management, and comments.

## Project Structure

- **/src**: Contains the source code for the React application.
  - **/components**: Reusable components used throughout the application.
  - **/pages**: Main pages of the application.
  - **/services**: API service functions to communicate with the backend.
  - **/context**: Context providers for managing global state.
  - **/hooks**: Custom hooks for reusable logic.

## Features

- **User Authentication**: Register, login, and manage users.
- **Blog Management**: Create, read, update, and delete blog posts.
- **Comments**: Add and manage comments on blog posts.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/RaulZvulunov/blog-frontend.git
   cd blog-frontend
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Run the development server:
   ```sh
   npm start
   ```

## Usage

- **Home Page**: Displays a list of blog posts.
- **Post Page**: Displays a single blog post with comments.
- **Create/Edit Post Page**: Form for creating or editing a blog post.
- **Login/Register Page**: Forms for user authentication.

## API Endpoints

Communicates with the backend API described in the backend README.

## Error Handling

- **Validation Errors**: Displayed in forms when user input is invalid.
- **General Errors**: Appropriate messages are shown for different error cases.
