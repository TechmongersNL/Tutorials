# What are you building?

The goal of this tech assessment is to create a plant watering tracker. You want to make sure that all the plants around your house are getting the proper amount of water and on the correct days.

It's a single page full stack application, here you can have a general idea of it:

> Wireframe Example: https://kyn.ac/SCR-20230223-fpj.jpeg

> Database Example: https://kyn.ac/SCR-20230223-g0f.png

## Tech Stack

### Frontend

- React
- CSS (no styling libraries)
- TypeScript (is a plus)

### Backend

- Node.js (Express & Sequelize) OR
- Python (FastAPI & SQLAlchemy)

## Features

### 1. Display a list of plants

Plants should be displayed with name, description and waterings history

### 2. Days since last watering

Plants should have a number indicating how many days since they were last watered. Based on that number, it indicates if the plant needs water today or not

### 3. Search plants

It's possible to search a plant by name

### 4. Sort plants

It's possible to sort plants by `all plants` and `plants that need water`

### 5. Add plants

There's button that when clicked displays a form. The form contains input for name, description and interval. Submitting the form creates a new plant in the database.

### 6. Add watering

Each plant has a button to add watering. Clicking the button creates a new entry for watering on that day and for that plant.

### 7. Delete a plant

Each plant is displayed with a delete button. Clicking the button deletes the plant from the database.
