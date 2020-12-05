# Eat the Burger

## Objective

The objective of this application is to create a burger logger using mySQL, Node, Express, Handlebars and a homemade ORM

## Installation
To use this application visit - https://thawing-waters-82560.herokuapp.com

## How it works
The Eat the Burger application allows the user to select a burger from the order menu and eat it or delete it. Eaten burgers move to the devoured board and can be deleted as well.
The user can also enter new burgers that will populate the order board and can be eaten or deleted.

## Demo
![Eat_the_burgerDemo](public/assets/Eat_the_burgerDemo.gif)


#### Directory structure

.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

## Credits
Eat the burger uses:
- MySQL, Node, Express and Handlebars
- For deployment it uses Heroku and JAWS

## Enjoy

I hope that you enjoy devouring burgers

- - -

All rights reserved Adriana Bonilla-Ramirez 2020



