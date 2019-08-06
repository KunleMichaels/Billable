# Frontend Coding Challenge

Welcome to the frontend coding challenge! Please read the following instructions carefully.

**The goal is to set up an application which enables the user to view and manage timecards.**

## Business need

The main goal is for the user to check the timecards at a glance. This allows users to take faster decisions and plan ahead of time.

Providing information to the customer increases transparency and reduces communication issues.

## Server-side

The application includes a small service for data fetching. The file `db.json` includes all the necessary data to achieve the goal. Please follow the steps below to start the server:

```
yarn or npm install .
yarn start or npm start
```

Check [json-server](https://github.com/typicode/json-server) for more information.

**there is a script to start both the server and the client at the same time**

After cloning the repository https://github.com/KunleMichaels/Billable.git follow the steps below

To Start the Application in development mode run 

1. yarn install
2. yarn start
3. cd client && yarn build (optional: to create a build file)


To Start the Application in production mode run 

1. yarn install
2. yarn start:prod
3. cd client && yarn build:prod  (optional: to create a build file)


After following the steps above the server should be live on http://localhost:5000 and the client on http://localhost:3000

To run the tests simply run

yarn test