# What's Sup?
What's Sup is a responsive web application that provides users with multiple recipe options based on your search criteria: cuisine, ingredients, calories and diet preferences. Registered users can create a favorite list of recipes.

## Screenshots

### Signup
![Signup_demo](https://github.com/jchanpark/WhatsSup/blob/main/frontend/docs/signup_demo.gif?raw=true)

### Favorite Cuisine
![Favorite_cusine](https://github.com/jchanpark/WhatsSup/blob/main/frontend/docs/favorite_cuisine.gif?raw=true)

### Search by Ingredients
![Search_by_ingredients](https://github.com/jchanpark/WhatsSup/blob/main/frontend/docs/search_by_ingredients.gif?raw=true)

### Daily meal plan by calories
![Daily_meal_plan](https://github.com/jchanpark/WhatsSup/blob/main/frontend/docs/daily_meal_plan.gif?raw=true)

### Popular recipes
![Popular_recipes](https://github.com/jchanpark/WhatsSup/blob/main/frontend/docs/popular_recipes.gif?raw=true)

### Responsiveness
![Responsiveness](https://github.com/jchanpark/WhatsSup/blob/main/frontend/docs/responsiveness.gif?raw=true)

## Setup

### Getting started
1. Fork and clone this repository to your local device.
2. Create a database 'postgreSQL' and create a .env file providing database credentials.
3. Register at `spoonacular.com` to get apiKey and provide it in .env file.
### Front-end
4. Navigate to front-end using `cd frontend`.
5. Install dependencies using `npm install`.
6. Start the server using `npm start`. The app will be served at `http://localhost:3000`.
### Back-end
7. Navigate to back-end using `cd backend`.
8. Install dependencies using `npm install`.
9. Start the server using `npm start`. The app will be served at `http://localhost:8080`.
10. You can reset the database by using `npm run db:reset` command.

## Dependencies
* Axios
* Express
* Morgan
* NodeJs
* Postgres
* React
* Sass
