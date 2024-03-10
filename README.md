<h1 align="center">Campus Compass</h1>

<div align="center">
    [Live Demo](https://jasminesjewelries-mohammed-design.netlify.app)
    The <b>Full-Stack CRUD Application</b> is scheduled to be uploaded by March 14th, 2024, marking the culmination of our diligent efforts and commitment to delivering a robust and efficient solution.
</div>

<br>

![Campus Compass](https://github.com/tech-moh-logy/Campus-Compass/assets/132733865/4b831400-400e-4fc0-a383-20ee16faf47d)

<div align="center">
    <h6>
        MOHAMMED
    </h6>
</div>

<br>
    
<div align="center">
    Campus Compass is a full-stack web application developed using the PERN (PostgreSQL, Express, React, Node.js) technology stack. It serves as a comprehensive Campus Management System, allowing users to manage campuses and students effectively.
</div>

## Overview

The goal of Campus Compass is to provide a user-friendly platform for managing student information and campus details. The application facilitates CRUD (Create, Read, Update, Delete) operations for both campuses and students, offering functionalities such as adding, editing, and deleting records.

## Features

- **Home Page View**: Users are greeted with a visually appealing home page that provides navigation to view all campuses and students.
- **All Campuses View**: Allows users to view a list of all campuses in the database, add new campuses, and delete existing ones.
- **Single Campus View**: Displays detailed information about a specific campus, including enrolled students. Users can also add or delete students from the campus and edit campus information.
- **Add Campus View**: Provides a form for users to enter information about a new campus, including name, address, description, and image URL.
- **Edit Campus View**: Allows users to edit existing campus information using a validated form.
- **All Students View**: Shows a list of all students in the database, with options to add and delete students.
- **Single Student View**: Displays detailed information about a specific student, including the campus they are enrolled in. Users can also edit or delete student records.
- **Add Student View**: Provides a form for users to add information about a new student, including first name, last name, email, image URL, and GPA.
- **Edit Student View**: Allows users to edit existing student information using a validated form.

## Technical Details

- **Frontend**: Developed using React.js for the user interface, with React Router for client-side routing and Redux for state management.
- **Backend**: Built using Node.js and Express.js for the server-side application, with Sequelize as the ORM for interacting with the PostgreSQL database.
- **Database**: PostgreSQL is used as the relational database management system to store campus and student data.

## Getting Started

To run Campus Compass locally:

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies for both the client-side and server-side applications using `npm install`.
4. Set up the PostgreSQL database according to the configuration specified in the project.
5. Start the backend server using `npm start` in the server directory.
6. Start the frontend application using `npm start` in the client directory.
7. Access the application in your web browser at `http://localhost:3000`.

## Version Control with Git and GitHub

Throughout the development process, version control is maintained using Git, a distributed version control system, and GitHub, a web-based Git repository hosting service. The following steps outline how Git commands are used to commit changes and manage project versions:

1. **Initializing a Git Repository**: The project directory is initialized as a Git repository using the `git init` command.

2. **Adding Files to the Staging Area**: Changes to project files are staged for commit using the `git add <file>` command. This adds modified, new, or deleted files to the staging area in preparation for the next commit.

3. **Committing Changes**: Staged changes are committed to the local repository using the `git commit -m "<commit message>"` command. A descriptive commit message is provided to document the changes made in the commit.

4. **Pushing Changes to GitHub**: To synchronize changes with a remote GitHub repository, the `git push` command is used. This uploads committed changes from the local repository to the corresponding branch on GitHub.

5. **Branching and Merging**: Git branching is utilized to work on features or bug fixes in isolation from the main codebase. Branches are created using the `git branch <branchname>` command, and changes from one branch are merged into another using the `git merge <branchname>` command.

6. **Pull Requests**: Collaborative development is facilitated through pull requests on GitHub. Developers create a pull request to propose changes from their forked repository to the original repository. Code reviews, discussions, and feedback can then be provided before merging the changes into the main codebase.7

## Contributors

This project was developed by MOHAMMED. 

## License

This project is licensed under the [MOHAMMED License](https://github.com/tech-moh-logy/MOHAMMED-License/blob/main/LICENSE). For more details, see the [LICENSE](https://github.com/tech-moh-logy/MOHAMMED-License/blob/main/README.md) file.
