<div align="center">
  <img src="https://raw.githubusercontent.com/sosoosz/PAS/refs/heads/main/imagens/logo_png.png" alt="Logo" width="150" />

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/sosoosz/PAS/refs/heads/main/imagens/cooknow.png" alt="Cooknow" width="100"/>
</div>


<div align="center">

<small>
The CookNow app helps users write recipes quickly and easily, allowing them to view all the recipes that have already been added.
</small>
</div>
<br>
  <p align="center">──────────────────────────────────────────────────────────────</p>
                    
<br>
<br>
<div>
  
### Introduction

<div>
<small>
The project consists of a mobile application and a website aimed at save recipes in a practical and efficient way, aimed at people who want to prepare meals quickly and simply. 
</small>
  
</div>

<br>

<div>
<img src="https://raw.githubusercontent.com/sosoosz/PAS/refs/heads/main/imagens/site.png" alt="Site"/>

<img src="https://raw.githubusercontent.com/sosoosz/PAS/refs/heads/main/imagens/recipe.png" alt="Recipe"/>

</div>
Here is our website homepage where we present our thoughts on the project, app features and more.

### Functionalities

- Commercial website promoting the application;
- Administrator access to added recipes, where you can manage them.
- Responsive website;
- API and mobile app built with Java in Android Studio;

### Roadmap API

- [x] Create the API 
  `php artisan install:api`, `php artisan make:controller Api/RecipeController --model=Recipe`

- [x] Code the structure of the initial menu to match the application

- [x] Display relevant information about the application in the home menu;

- [x] Style the main menu;

- [x] Style the navigation bar;

- [x] Code the user profile structure to allow data modification;

- [x] The administrator can create, edit and delete recipes, which is shown through a table.


### Roadmap App


- [x] `RecipeListAdapter` - The class responsible for adapting the recipe data for display in a list (RecyclerView).
- [x] `RecipeViewHolder` - Manages and holds references to layout elements to efficiently display each item in the recipe list.
- [x] `Recipe` - Represents a recipe in the "recipes" table. It contains the recipe name, ingredients, and creation date.
- [x] `RecipeTakeActivity` - The `RecipeTakeActivity` is a screen where the user can create or edit recipes. It allows the user to input the name and ingredients of the recipe and then makes a request to the API to create or update the recipe on the server.
- [x] `LoginActivity` - Handles user login functionality, where the user can enter their credentials (username and password) to log in to the app.
- [x] `MainActivity` - This activity displays a list of recipes and allows the user to interact with them by viewing details, adding new recipes, or accessing their profile.
- [x] `ProfileActivity` - Display the logged-in user's profile, showing the username and allowing them to log out.
- [x] `RecipeResponse` - This class represents the response received from the API when fetching a list of recipes.
- [x] `RegisterActivity` - This activity manages the process of user registration, allowing new users to create an account by submitting their username and password.
- [x] `UpdateRecipeResponse` - This class is designed to model the response returned when a recipe is updated via the API. It captures the updated Recipe object, which can then be used by the application to reflect the changes in the user interface.
- [x] `ApiService` - This interface defines the key API endpoints to communicate with the backend server for handling recipe data. The ApiService interface contains methods to fetch a list of recipes, create new recipes, and update existing recipes.
- [x] `RecipeClickListener` - To define the behavior when a recipe item is clicked in the UI. Typically, this interface would be implemented in the activity or fragment that displays the list of recipes, allowing the app to respond to user interactions such as navigating to a detailed view or editing a recipe.

- [x] layout
  - [x] `activity_main` - XML layout file responsible for designing the main screen of the app. It includes the recipe list and interactive buttons.
  - [x] `activity_recipe_take` - XML layout file for the add/edit recipe screen, featuring input fields for name, ingredients, and save options.
  - [x] `recipe_list` - Layout for individual items in the recipe list. Defines how each recipe's information is displayed (e.g., name and pinned status).
  - [x] `activity_login` -  XML layout file for the login screen with fields for username, password, and login button.
  - [x] `activity_register` -  XML layout file for the registration screen with input fields for creating a new account.
  - [x] `activity_profile` - This XML layout file is for a simple screen that displays a username and a logout button.
 
     
- [x] Room Database classes
  - [x]  `UserDao` - The Data Access Object (DAO) interface that defines the database functions related to users. It contains methods like insertUser() to insert a new user and login() to query the database for a user based on their username and password.
  - [x] `User` - The model class that represents the structure of the "users" table in the database. It contains fields like id, username, and password to store user data. It also provides getter and setter methods to access and modify these fields.
  - [x] `AppDatabase` - The database class that sets up the Room database. It holds the database instance and provides access to the DAOs, like UserDao. It uses the Room.databaseBuilder() to create the database and ensures that operations are performed on a background thread using the ExecutorService.

### Database Structure
## API Database
In the next image is the database of the api:
<div align="center">
  <img src="https://raw.githubusercontent.com/sosoosz/PAS/refs/heads/main/imagens/bd.png" alt="Cooknow" width="600"/>
</div>

## App Database (Room Database)
In the application, using Room DataBase, the database consists of a single table named recipes, which includes the following fields:
- `Id (INTEGER)`: A unique identifier for each recipe; 
- `Username (TEXT)`: The username;
- `Password (TEXT)`;


This streamlined design focuses on simplicity while supporting the core functionalities of the app.

### Built with
- Android Studio;
- VSCode;
- JSON
- Room Database;
- Laravel;
- HTML;
- CSS;
- PHP;
- JAVA;
- Recycler View.


## Authors
- [@NazareCavaco](https://github.com/NazareCavaco)
- [@sosoosz](https://github.com/sosoosz)
