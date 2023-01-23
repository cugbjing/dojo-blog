# Generic Blog React App
Basic react app, including generic CRUD operation on data. Very good example for the following topis:
- React Hooks: useState, useEffect, useHistory, useParams, and custom hook
- React Router
- CRUD operations through: GET, POST, DELETE
- Handle errors in http call
- Add cleanUp function in useEffect (however, my local project did not have this issue when swithing between different components)

## Available Scripts
- `npm start`: run the app, for local test
- `npm run build`: for production build
- `npx json-server --watch data/db.json --port 8000`: run the backend as the REST API, data see `data/db.json`

## Backend
The back end is simulated by using package `json-server`

## Reference
[Youtube Link](https://youtube.com/playlist?list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d)
