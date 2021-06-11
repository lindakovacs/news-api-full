# Project Diploma New Explorer API Front End + Back End
* Part of the [Practicum by Yandex](https://practicum.yandex.com/) Web Development Bootcamp Curriculum.

Demo link - Front-end TBD 
http://lkovacs-news.students.nomoreparties.site/

# news-explorer-api-frontend
The "New Explorer API" has authorization and registration handled by the back-end server and handles articles and users. 

### Server
- Back-end Repo: https://github.com/lindakovacs/news-explorer-api
- Front-end Repo: https://github.com/lindakovacs/news-explorer-frontend.git 
- Api hosted on AWS Cloud
- Server IP: 3.142.148.60
- Back-end/Api: http://lkovacs-news.students.nomoreparties.site/
- Front-end: TBD

The Express NodeJs project implements the API in the backend.

A responsive website using HTML5, CSS3 (flexbox, grid, BEM), JavaScript, built following the design mokup in Figma.
This adaptive page includes form validation, interactive popups, fade-in and fade-out animations, functional like and delete buttons, modular JavaScript, and Object Oriented JS design.

The React Framework is used to add functionality to Form Fields in a Popup Box and save the edited values. Used BEM methodology with a nested file structure.

The server-side web framework Express.js is used to help deploy our own back-end server faster, work with databases, set up security and testing, as well as deploying the back end on a remote machine. The goal of all this is to create a server with an API and user authentication.

The project interactivity includes:

- Popup modals for: signup/signin
- Adding new articles and Deleting user's own articles only
- Liking and unliking articles

The current version is responsive gets profile information and images via API, and has functioning modal popups.
The project adapts to the width of various devices (from 320px to 1280px). The project is based on dynamically editing the profile information on popup modals and adding cards of places and image popups. Everything is rendering responsively adapting to different screen sizes.

**Features**

- Form Popup Modal: editing profile information, adding/deleting articles with images, titles, taxt, date, link, source, image
- Forms are validated using javascript. card popup for each card with Delete and Like button.

**Technologies**

Stack: HTML5, CSS3, flexbox, grid layout, BEM, Media queries, transition, JavaScript/JSX, DOM, Debugging Git, Git/Github, Figma, Form validation, OOP, Webpack, NPM, React, React components, React hooks, Node.js, Express.js, AWS

**Figma**

The website was made up according to the Figma layout requirements:

- [Link to the project in Figma](https://www.figma.com/file/z1bxDn7eBEDlsDhnZ9dtin/Your-Final-Project?node-id=0%3A1)

- Export images directly from Figma and optimize them [here](https://tinypng.com/), so your project loads faster.

**Articles**

All the articles are pulled from the server using the API.


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
