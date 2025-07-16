# alx-project-0x01: Daily Contents Application

## Project Description
This project is a foundational Next.js application built with TypeScript, Tailwind CSS, and ESLint. It demonstrates core front-end development concepts including component-based architecture, client-side navigation, data fetching (using `getStaticProps`), and interactive forms within modals for adding new content.

The application serves as a "Daily Contents" platform, allowing users to browse a list of posts and users, and interact by adding new entries through modal forms.

## Features

* **Project Setup**: Initializes a Next.js application with TypeScript, ESLint, Tailwind CSS, and import aliases.
* **Navigation**: Implements seamless client-side navigation between the Home, Posts, and Users pages using Next.js's `Link` component.
* **Posts Display**: Fetches a list of posts from a public API (`jsonplaceholder.typicode.com`) at build time using `getStaticProps` and displays them using a reusable `PostCard` component.
* **Add Post Modal**: Provides an interactive modal form (`PostModal`) to allow users to add new post entries to the displayed list dynamically.
* **Users Display**: Fetches a list of users from a public API (`jsonplaceholder.typicode.com`) at build time using `getStaticProps` and displays them using a reusable `UserCard` component.
* **Add User Modal**: Provides an interactive modal form (`UserModal`) to allow users to add new user entries to the displayed list dynamically.
* **Component Reusability**: Employs a structured component hierarchy (`common`, `layout`) to promote reusability and maintainability.
* **Type Safety**: Utilizes TypeScript interfaces (`interfaces/index.ts`) to ensure strong typing across components and data structures, enhancing code robustness.
* **Styling**: Leverages Tailwind CSS for rapid and efficient styling, creating a responsive and visually appealing user interface.

## Technologies Used

* **Next.js**: React framework for production.
* **React**: JavaScript library for building user interfaces.
* **TypeScript**: Strongly typed superset of JavaScript.
* **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
* **ESLint**: Pluggable linting utility for JavaScript and JSX.
* **`create-next-app`**: Tool for quickly setting up Next.js projects.

## Project Structure