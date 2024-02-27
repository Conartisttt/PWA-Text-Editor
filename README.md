# PWA-Text-Editor

## Table of Contents

[Description](#description)
<br>
[Technologies Used](#technologies-used)
<br>
[Usage](#usage)
<br>
[Credits](#credits)

## Description

This is a text editor that allows users to create notes or code snippets so that they can be reliably retrieved for later use. It is a single-page application that meets the PWA criteria. It features a number of data-persistence techniques that serve as redundancy in case one of the options is not supported by the browser. It can be used with or without an internet connection.

This application is deployed using Render [here](insert link to deployed application)

## Technologies Used

- Webpack for bundling
- Service Worker for use offline
- IndexedDB for database storage
- Mongoose ORM

## Usage

- When you enter the command to invoke the application, `node index.js`, the server is started and the Mongoose models are synced to the MongoDB database

- When you open API GET routes in Insomnia for users and thoughts, the data for each of these routes is displayed in a formatted JSON

- When you test API POST, PUT, and DELETE routes in Insomnia, you are able to successfully create, update, and delete users and thoughts in the database

- When you test API POST and DELETE routes in Insomnia, you are able to successfully create and delete reactions to thoughts and add and remove friends to a user's friend list

## Credits

- Application written by Conner Martin aka Conartisttt
