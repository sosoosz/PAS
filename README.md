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
The project consists of a mobile application and a website aimed at save recipes in a practical and efficient way. Aimed at people who want to prepare meals quickly and simply. The app offers features such as recipe search and also the ability to pin recipes for easy future access, making the cooking experience more accessible and productive.
</small>
  
</div>

<br>

<div>
<img src="https://raw.githubusercontent.com/sosoosz/PAS/refs/heads/main/imagens/site.png" alt="Site"/>

</div>
Here is our website homepage where we present our thoughts on the project, app features and more.

### Functionalities

- Commercial website promoting the application;
- Users can give their opinion about the application;
- Responsive website;
- API-based mobile app built with Java in Android Studio;

### Roadmap API

- [x] Create the API using Laravel  
  `composer create-project laravel/laravel Cooknow`

- [x] Code the structure of the initial menu to match the application

- [x] Display relevant information about the application in the home menu;

- [x] Style the main menu;

- [x] Style the navigation bar;

- [x] Make the comments section functional;

- [x] Style the comments section;

- [x] Code the user profile structure to allow data modification;

- [x] Code to enable an admin user to moderate comments;

- [x] Add a favorites table for use in the application;

### Roadmap App

- [x] Room Database classes
  - [x] `MainDAO` - The class that holds the database functions, such as insert, query, update, and delete operations for the recipes table.
  - [x] `Recipe` - The model class that represents the structure of the recipes table in the database. It contains the fields and methods required to handle recipe data.
  - [x] `RecipeClickListener` - Handles interactions and behaviors when clicking on items in the recipe list.
  - [x] `RecipeListAdapter` - The class responsible for adapting the recipe data for display in a list (RecyclerView).
  - [x] `RecipeViewHolder` - Manages and holds references to layout elements to efficiently display each item in the recipe list.
  - [x] `RoomDB` - Implements the Room Database, enabling the creation and access to the recipes table.
- [x] `MainActivity` - The main screen of the app, where saved recipes are displayed and managed. It allows interactions with the recipe list and highlights pinned recipes.
- [x] `RecipeTakeActivity` - The screen for adding or editing recipes. It allows users to input the necessary data, such as name and ingredients.
- [x] layout
  - [x] `activity_main` - XML layout file responsible for designing the main screen of the app. It includes the recipe list and interactive buttons.
  - [x] `activity_recipe_take` - XML layout file for the add/edit recipe screen, featuring input fields for name, ingredients, and save options.
  - [x] `recipe_list` - Layout for individual items in the recipe list. Defines how each recipe's information is displayed (e.g., name and pinned status).

### Database Structure
## API Database
In the next image is the database of the api:
<div align="center">
  <img src="https://raw.githubusercontent.com/sosoosz/PAS/refs/heads/main/imagens/bd.png" alt="Cooknow" width="600"/>
</div>

## App Database (Room Database)
In the application, using Room DataBase, the database consists of a single table named recipes, which includes the following fields:
- `Id (INTEGER)`: A unique identifier for each recipe; 
- `Name (TEXT)`: The name of the recipe;
- `Ingredients (TEXT)`: A list of ingredients used in the recipe;
- `Pinned (BOOLEAN)`: Indicates whether the recipe is pinned or not;
This streamlined design focuses on simplicity while supporting the core functionalities of the app.

### Built with
- Android Studio;
- Room Database
- Laravel
- HTML
- CSS
- PHP
- JAVA
- Recycler View


## Authors
@NazareCavaco
@sosoosz
