# Book List

The Book List is a web application for managing a list of books in a CRUD fashion with a REST architecture.

## Technical Requirements

- used the latest version of React;
- used hooks (where necessary);
- used Typescript, 
- used only functional components;
- usad of Context;
- used CSS frameworks;
- avoided using third-party packages (like Redux, mobX, axios, formik, yup, react-hook-form etc.);

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone this repository to your computer:

### `git clone insert_repository_link_here`

2. Install the required dependencies using npm:

### `npm install`

3. Start the application. The application will be accessible in your web browser at http://localhost:3000.

### `npm start`

## Description

The application has two main pages: Dashboard and Add a Book/Edit a Book.

### Dashboard (Information Panel):

  On this page, you'll see a table of books with the following columns:
- Book Title
- Author Name
- Category
- International Standard Book Number (ISBN)
- Created At (date and time following the format "12 March 2022, 8:35 AM")
- Modified/Edited At (date and time following the format "13 March 2022, 1:48 PM")

  In the "Actions" column, there are three different buttons:

- Edit: Redirects to the book edit page with pre-filled fields.
- Delete: Only available for deactivated records, removes the book from the database and the list.
- Deactivate/Reactivate: Highlights the record as deactivated or reactivated. Also marks the record as deactivated in the database.

  Above the table is a filter/dropdown where the user can select one of the following options:

- Show All (default)
- Show Active
- Show Deactivated

There is also a link to the "Add a Book" page on this page.

### Add a Book/Edit a Book. Functionality:
  This page features a form with the following fields:

- Book Title (text, required)
- Author Name (text, required)
- Category (select with a few dummy options, required)
- International Standard Book Number (ISBN) (number, required)
- The form has a "Submit" button, which can either be "Add a Book" or "Edit Book" based on the user's action. There is also a link to the "Dashboard" page on this page.

