# Pinterest Frontend

## Introduction
Developed a full-stack web application which clones the pinterest web application. It features user signup, exploration, pin uploading, commenting, and deletion of pins.

## Features
1. User can login/signup. For login/signup, hashed users ID is stored in the browser's local storage.
2. User can upload/delete thier own pins; pins are simple pictures. Pins are stored as Blobs on GCP.
3. User can follow other users, whose pins and random pins will be visible to him on the home page.
4. User can search for specific pins. For example, if he searches for 'Cat', he will see all pins associated with 'Cat' as pin heading.
5. User can comment on other user's pins only if he follows him.
6. User can also take up specific roles - user, seller, or admin. User and seller have the same functionalities, whereas admin can delete any pin/user.
7. User can see pages such as profile page, search page etc only if he is logged in.
8. Used SQL databases for mapping all the relationships between different tables and tasks.

### Technologies used
1. JavaScript
2. Node.js
3. React.js

Note: This repo is for the frontend server. Repo for [Backend](https://github.com/ekam14/Pinterest-Backend). 