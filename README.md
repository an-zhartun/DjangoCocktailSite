## Project Description

This is a web application for storing and managing cocktail recipes, built with Django and Django REST Framework. The application allows users to view, add, update, and delete cocktails, as well as manage favorite recipes. A user registration and authentication system is implemented to personalize the functionality.

Screenshots of the application's interface and functionality will be provided below for visual reference.


## Key Features:

- **Registration and Authentication**: Users can create accounts and log in to access personalized features.
- **Home Page**:
  - **Before authentication**: Access to "Home", "Cocktails", and "Login" sections.
  - **After authentication**: Access to "Home", "Cocktails", "Create Cocktail", "My Cocktails", "Favorites", and "Logout" sections.
- **"Cocktails" Page**: A list of all cocktails with filtering by name and type (alcoholic/non-alcoholic). Users can update cocktails or add them to favorites by hovering over the cocktail card.
- **Creating a Cocktail**: Users can add a new cocktail by selecting a category, filling in all fields, and uploading an image (either from a PC or via a link).
- **"My Cocktails" Page**: Cocktails created by the current user with an option to archive them.
- **"Favorites" Page**: A list of cocktails added to the user's favorites.
- **Cocktail Detail Page**: Full description of the cocktail, including ingredients and preparation method, with the option to add to favorites and manage comments (add, delete, reply).




# Technology Stack

- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS, JavaScript
- **Database**: Postgresql
- **Authentication**: Django Authentication, JWT
-  **Libraries**: SQLAlchemy, django-filter


## Registration and Authentication
Once the application is running, you can register and log in to access the full functionality of the application.

## Working with Cocktails
- **Viewing all cocktails**: Navigate to the "Cocktails" page to view the list of all available recipes.
- **Creating a new cocktail**: Registered users can add a new cocktail via the form on the "Create Cocktail" page.
- **Updating and Archiving**: The owner of a recipe can update and archive their cocktails.
- **Adding to Favorites**: Any user can add a liked cocktail to their favorites.
- **Comments**: Users can comment on cocktails, reply to comments, and delete them.
<br><br><br>

# Instructions for running the project
## Steps to run the project

### 1. Cloning the repository
Clone the repository using the Git command:

```bash
git clone https://github.com/an-zhartun/DjangoCocktailSite.git
```
### 2. Building Docker containers
```bash
docker-compose build
```

### 3. Starting the containers
```bash
docker-compose up
```
If you need to run the containers in the background, use the command:

```bash
docker-compose up -d
```

### 4. Opening the application

After the project has been successfully launched, the application will be available at the following address:

```bash
http://localhost:8000
```
### 5. Stopping the containers
```bash
docker-compose down
```
This command will stop all running containers and remove them, while preserving any data created in persistent storage (volumes).
#### To run the project, it is necessary to create a .env file.

<br><br>

## Screenshots

### 1. Home Page before Authentication:
This is the home page of the web application, available to unauthenticated users. Sections such as "Home", "Cocktails", and "Login" are visible. This is the basic functionality accessible to all visitors.
![Home1](https://github.com/an-zhartun/an-zhartun/blob/images/images/Главная1.png?raw=true)

### 2. Login and Registration Page:
These are the login and registration forms, where users can either register to create a new account or log in with an existing account.
![Login](https://github.com/an-zhartun/an-zhartun/blob/images/images/вход.png?raw=true)
![Registration](https://github.com/an-zhartun/an-zhartun/blob/images/images/регистрация.png?raw=true)

### 3. Home Page after Authentication:
This shows how the interface changes after the user logs in. Additional sections such as "Create Cocktail", "My Cocktails", "Favorites", and a "Logout" button are now available.
![Home2](https://github.com/an-zhartun/an-zhartun/blob/images/images/Главная6.png?raw=true)

### 4. Cocktails Page:
This page displays a list of all cocktails. Users can view cocktail cards, filter them by name and type (alcoholic/non-alcoholic). By hovering over a cocktail card, users can update the recipe or add it to their favorites.
![Cocktails](https://github.com/an-zhartun/an-zhartun/blob/images/images/список2.png?raw=true)

### 5. Creating a Cocktail:
This is the form for creating a new cocktail. The user can select a category, fill in the necessary fields, and upload an image either from a computer or via a link to add a new recipe to the database.
![Creating](https://github.com/an-zhartun/an-zhartun/blob/images/images/создание.png?raw=true)

### 6. Updating a Cocktail:
This form shows how an existing cocktail can be updated by changing the information about its ingredients, preparation method, or image.
![Updating](https://github.com/an-zhartun/an-zhartun/blob/images/images/обновление.png?raw=true)

### 7. My Cocktails:
The "My Cocktails" page displays a list of all recipes created by the user. Users can archive or edit their cocktails here.
![MyCocktails](https://github.com/zenastyaz/Private/raw/main/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-05-11%20%D0%B2%2017.19.19.png?raw=true)

### 8. Favorites:
This page shows how cocktails added to the user's favorites are displayed. Users can easily view and manage their favorite recipes.
![Favorites](https://github.com/an-zhartun/an-zhartun/blob/images/images/избранное.png?raw=true)

### 9. Cocktail Detail Page:
The detailed cocktail page shows the full description of the cocktail, including ingredients, preparation method, and the option to add it to favorites. Comment management functions are also available.
![Detail](https://github.com/zenastyaz/Private/raw/main/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-05-11%20%D0%B2%2018.01.50.png?raw=true)

### 10. Comment Form:
This screenshot shows how users can leave comments on cocktail recipes. The form allows users to write and submit a comment.
![Comment Form](https://github.com/an-zhartun/an-zhartun/blob/images/images/Формакоммент.png?raw=true)

### 11. Comment and Reply Form Screenshot:
This screenshot shows a comment added to a cocktail, with a visible reply form.
![Comment Form2](https://github.com/an-zhartun/an-zhartun/blob/images/images/коммент%20.png?raw=true)

### 12. Child Comment:
This screenshot displays a child (reply) comment that a user left in response to the main comment.
![Comment Form3](https://github.com/zenastyaz/Private/raw/main/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-05-11%20%D0%B2%2017.22.30.png?raw=true)

These screenshots help better understand how the web application's functionality works at each stage of user interaction.
