<h1 align="center">
  <a name="logo" href="https://aa-listen-up.herokuapp.com/"><img src="https://i.ibb.co/GvTQmVt/3302a83c84141d31265b51c683e2c0ba-removebg-preview.png" alt="Listenuplogo" width="300"></a>
  <br>
  Listenup Documentation
</h1>

<h4 align="center">Listenup is a cataloging website that allows users to interact with a database of podcasts. Users can sign up and register to create and edit playlists.</h4>
<h1 align="center">
  <a name="logo" href="https://aa-listen-up.herokuapp.com/"><img src="https://i.ibb.co/wMYVZYS/icons8-javascript-96.png" alt="js-logo" width="50"></a>
  <a name="logo" href="https://aa-listen-up.herokuapp.com/"><img src="https://i.ibb.co/xMxSMkw/icons8-pug-96.png" alt="pug-logo" width="50"></a>
  <a name="logo" href="https://aa-listen-up.herokuapp.com/"><img src="https://i.ibb.co/VLYp5m1/icons8-css3-96.png" alt="css-logo" width="50"></a>
  <a name="logo" href="https://i.ibb.co/VpGfh8w/icons8-postgresql-96-1.png"><img src="https://i.ibb.co/VpGfh8w/icons8-postgresql-96-1.png" alt="psql-logo" width="50"></a>
</h1>

 ![](https://img.shields.io/badge/Tools-Nodemon-informational?style=flat&logo=Nodemon&logoColor=white&color=ff8300) ![](https://img.shields.io/badge/Tools-Node.js-informational?style=flat&logo=Node.js&logoColor=white&color=ff8300) ![](https://img.shields.io/badge/Tools-Git-informational?style=flat&logo=Git&logoColor=white&color=ff8300) ![](https://img.shields.io/badge/Tools-Postman-informational?style=flat&logo=Postman&logoColor=white&color=ff8300) ![](https://img.shields.io/badge/Tools-PostgreSQL-informational?style=flat&logo=PostgreSQL&logoColor=white&color=ff8300) ![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=JavaScript&logoColor=white&color=ff0000) ![](https://img.shields.io/badge/Code-HTML-informational?style=flat&logo=HTML5&logoColor=white&color=ff0000) ![](https://img.shields.io/badge/Code-CSS-informational?style=flat&logo=CSS3&logoColor=white&color=ff0000) 
 ![](https://img.shields.io/badge/Tools-npm-informational?style=flat&logo=NPM&logoColor=white&color=ff8300)
 
 <div align="center">
  <sub>Built with ❤︎ by
  <a href="https://github.com/julia-richards">Julia Richards</a>, 
  <a href="https://github.com/Cmolerov">Carlos Molero</a>, 
  <a href="https://github.com/jamestlee513">James Lee</a> and
  <a href="https://github.com/miguelcoria94">Miguel Coria.</a>
</div>

A live version of our application can be found [here](https://aa-listen-up.herokuapp.com/).

<h1 align="center">
  <a name="logo" href="https://aa-listen-up.herokuapp.com/"><img src="https://i.ibb.co/RvbxMX6/d143e1526e431e9668ad77077c6d4eae.png" alt="Listenup-home" width="80%"></a>
</h1>

## Overview

Listenup is podcast cataloging web application inspired by Goodreads. As a logged out user, you only have the ability to browse the front page. As a logged in user you have the ability to rate and review podcasts. As a logged in user you also have the ability to create, update and edit playlist. Listenup is built with Express JS, The Pug Template Engine, and Vanilla CSS.

![home gif](https://github.com/miguelcoria94/readme-for-listenup/blob/main/ezgif.com-gif-maker.gif)

<br>

<h1 align="center">
  Features
</h1>

## User Authenication

Users can securely create an account using our login and logut feature. Listenup uses bcrypt to securely hash passwords so that no plain text passwords are ever stored in the database. listenup also uses various middleware functions when processing request and responses so that we know a user is who they say they are. Certain routes also require user authenication for pages to be accessed. [CHECK IT OUT](https://github.com/jamestlee513/listen-up/blob/main/routes/users.js)

![user auth gif](https://github.com/miguelcoria94/readme-for-listenup/blob/main/b4e89c9ab44e6ba8c4d53650b21ce3e0%20(1).png)

Listenup's register and login forms have input validations to enforce clean data submission and protect the integrity of the data submitted.

![user register gif](https://github.com/miguelcoria94/readme-for-listenup/blob/main/ezgif.com-gif-maker%20(2).gif)






