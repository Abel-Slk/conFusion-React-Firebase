# restaurant-app-react-firebase

A restaurant website with a React + Redux frontend and a Firebase backend. Users can log in using their username and password or using their Google account. Logging in enables users to add comments to the dishes in the menu, as well as add dishes to their personal list of favorites.

The app is hosted at: https://confusionserver-b29fc.web.app

# Frontend
Implemented as a single page React app. Navigation is done via React Router. Application state is managed by Redux. 
## Technologies used
- ES6 JavaScript 
- React
- Redux
- Redux-Thunk
- React Router
- Reactstrap (Bootstrap)
- React Transition Group and React Animation Components for animation

## Usage
To run the frontend React client locally:

`npm start`

# Backend
Implemented using Firebase BaaS. 

All data is stored entirely on Firebase servers: 
- the restaurant database (dishes, leaders, promotions, comments, lists of favorites) is stored in the Cloud Firestore database
- Image resources are stored in Firebase Storage

Authentication via Google is also enabled through Firebase.
