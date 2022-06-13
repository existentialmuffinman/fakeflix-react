# FAKEFLIX

Fakeflix: a Netflix clone

This application was initially made in class components and later converted into functional components with hooks to keep it future-ready. It was mainly used as a way to learn React and state management.

The application implements authentiction using firebase and consists of a landing made to emulate the movie list and title/description display as seen in Netflix. The user will be able to slect a movie to view more information on it and, save it as their favourites. The API used to fetch movie information here is [TMDB](https://www.themoviedb.org/), and user specific information and authntication is stored in Firebase.

# Running the Application

use the `npm run start` command in the project directory to run the application. The application will be available on `http://localhost:3000/`

# Project layout
The file structure for this project is given below
```
fakeflix-react/
├─ src/
│  ├─ components/
│  ├─ context/
│  ├─ pages/
│  ├─ firebase.js
│  ├─ App.js
│  ├─ index.css
│  ├─ index.js
│  ├─ Requests.js
├─ .env
├─ .firebaserc
├─ firebase.json
├─ package-lock.json
├─ package.json
├─ postcss.config.js
├─ README.md
├─ tailwind.config.js
```
A few key points on the above are:
| Folder/File | Description |
|-------------|-------------|
|`components/`| containsns all the components implemented in the reacapplicationon |
|`context/`| contains the contexts used in the application along with their handlers |
|`pages`| contains all the views for the corresponding routes defined in the application |
|`firebase.js`| contains the firebase configuration setup fetched from `.env` |
|`App.js`| entrypoint for the React application into the `index.html` file |
|`Requests.js`| contians all the calls to the TMDB API to fetch movies to be displayed |
|`.firebaserc/firebase.json`| configurations for firebase |
|`postcss.config.js/tailwind.config.js`| configurations for tailwind |
