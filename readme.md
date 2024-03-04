# README for CRUD Web Application - Book Management

## Project Overview

This project involves creating a web application that implements CRUD functionality for managing a reading list. The application allows users to seamlessly add, edit, and delete books from their reading list, and it integrates an API to search for books and add them to the reading list.

### Frontend:

1. **Book List (Read):**
   - Implemented a responsive frontend that dynamically displays a list of books.
   - Utilized the `fetch()` function to seamlessly retrieve book data from the NodeJS backend via API calls.
   - Applied JSON-to-JavaScript object conversion for dynamic HTML rendering.

2. **Book Addition (Create)**
   - Designed an intuitive form for users to add new books to their reading list.
   - Captured form data and optimized the user experience by sending it to the backend using `fetch()` with a POST request.
   - Enabled real-time updates to the book list upon successful book creation.

3. **Delete:**
   - Delete button for each book in the list.
   - Implemented a click event handler to send the book ID via `fetch()` and perform a POST request to the backend.
   - Updates to the book list after successful deletion.

4. **Book Updating (Update):**
   - Allowing users to update existing book information.
   - Utilized PUT or PATCH requests to the backend for efficient book updates.
   - Considered user interface elements for a smooth editing experience.

5. **Integrated Book Search using API:**
   - Implemented a robust book search feature using an external API.
   - Allowed users to search for books by title or author, seamlessly integrating the fetched book data into the application.
   - Demonstrated the ability to work with external APIs to enhance application functionality.

### Backend:

 **Express.js Backend:**
   - Established backend routes for GET, POST, and DELETE operations.
   - Leveraged Express.js to efficiently handle routes and corresponding callback functions.
   - Stored book data persistently by saving it to a file using NodeJS fs or fs-promises module.


## Tools Used

- **Frontend:**
  - JavaScript for dynamic and interactive user interfaces.
  - Tailwind CSS for streamlined and responsive styling.

- **Backend:**
  - NodeJS for server-side JavaScript development.
  - Express.js for efficient routing and handling HTTP requests.
  - NodeJS fs and fs-promises for persistent data storage.


