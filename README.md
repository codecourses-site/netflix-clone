# How to Learn React By Building Netflix

## Table of Contents

| No. | Topics                                    |
| --- | ----------------------------------------- |
| 1   | [About Code Courses](#about-code-courses) |
| 2   | [Live Demo](#live-demo)                   |
| 3   | [Screenshot](#screenshot)                 |
| 4   | [Technologies](#technologies)             |
| 5   | [Running the demo](#running-the-demo)     |
| 6   | [Useful links](#useful-links)             |

<a id="about-code-courses"></a>

## 1. About Code Courses

<a href="https://codecourses.site">Code Courses</a> is a website where people learn about coding and different technologies/frameworks/libraries. To help people learn, all of the courses are **FREE** and **DETAIL**. Hopefully, after following the content on Code Courses, you will find your dream jobs, and build any applications that you want.

<a id="live-demo"></a>

## 2. Live Demo

- For the full course, You can refer to this [link](https://codecourses.site/react/how-to-learn-react-by-building-netflix-ep-1/).

- You can refer to this [Youtube video](https://www.youtube.com/watch?v=YrHeMI-RIFU) for the live demo.

<a id="screenshot"></a>

## 3. Screenshot

![](./screenshots/screenshot.png)

<a id="technologies"></a>

## 4. Technologies

This demo uses:

- React.js
- Firebase

<a id="running-the-demo"></a>

## Running the demo

To run the demo follow these steps:

1. Download the repository [here](https://github.com/codecourses-site/netflix-clone/archive/main.zip) or by running `git clone https://github.com/codecourses-site/netflix-clone.git` and open it in a code editor.
2. [Head to Firebase and create a new project](https://console.firebase.google.com)
3. Create a file called **.env** in the root folder of your project.
4. Import and inject your secret keys in the **.env** file containing your CometChat and Firebase in this manner.

```js
REACT_APP_FIREBASE_API_KEY = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
REACT_APP_FIREBASE_AUTH_DOMAIN = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
REACT_APP_FIREBASE_DATABASE_URL = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
REACT_APP_FIREBASE_STORAGE_BUCKET =
  xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
```

5. Make sure to exclude **.env** in your gitIgnore file from being exposed online.
6. Run the following command to install the app.

```sh
    npm install
    npm run start
```

Questions about running the demo? [Open an issue](https://github.com/codecourses-site/netflix-clone/issues). We're here to help ✌️

<a id="useful-links"></a>

## Useful links

- 🔥 [Firebase](https://console.firebase.google.com)
- 🔷 [React.js](https://reactjs.org/)
