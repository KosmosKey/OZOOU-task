# Starting the environemnt

# Backend

- You need to create a postgress table named `todo` and `todochilren`
- When you have created table for `todo` and `todoChildren` you need to make columns for them
- `todo` table will accept these columns with data types:

  - id: text
  - title: text
  - status: text
  - created_at: text

- `todochilren` table will accept these columns with data types:

  - id: text
  - title: text
  - status: text
  - created_at: text

- Once that is done you go to backend folder `/backend`
- run `npm i` and then `npm run start` or `npm start` (I am using nodemon to start the server)
- You need to go edit configurations for postgress in `/backend/helpers/index.js`. I have set up my own, but you can of course change it

Once that is done you are good to go with the API's (http://localhost:3001/oozou) - You can also test it on postman

# Frontend

Front end is pretty simpler

- Go to `/frontend` Run `npm i` and then `npm run dev`
- In `/frontend/api/axios.js` you need to change baseUrl to `http://localhost:3001/oozou` so it can connect to the API

# Important

- Frontend and Backend needs to run together at the same time other wise frontend will not connect api to the backend.

Otherwise i hope you will enjoy looking at the code and see how everything is done 😊
