# TIC TAC TOE

# Spec

# Frontend

Design a Single Page Application (SPA) in React using routing. The app should have 3 pages:

- ## Login Screen

A screen with a form where the user can either sign up (name, email, password) or log in (email, password). This will then direct him to the next screen

- ## Game Screen

A game screen where the user plays against the computer a game of Tic Tac Toe (naughts and crosses). Basic computer AI is expected but you can expand at will. Research will do you good here.

- ## Details Screen

This will be a screen to display user info:

- ability to change username
- view count of wins / losses
- ability to reset count of wins / losses

Store credentials / details in local storage if you choose not to do the backend component

# Backend

Utilise mysql, sequelize, nodejs and graphql to build a backend that stores a User table (email - primary key, name, password) and a Stats table (email - foreign key, win_count, loss_count) with appropriate methods based on the frontend functionality.

# Deployment

For assignment completion, deployment of both backend and frontend is required (possibly simplest to do with Heroku). Research methods to do such and wire the frontend to the deployed backend/server link. Present your frontend link and your code. If the app does not run, the code will not be checked.
