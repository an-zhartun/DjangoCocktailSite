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

