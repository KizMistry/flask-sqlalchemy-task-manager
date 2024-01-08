# Task Manager App

## Overview

This is a simple Personal Task Manager web application built using Flask and SQLAlchemy. The app is designed to serve as a personal task organization tool, allowing a single user to create, edit, and delete tasks. Each task can have a name, description, due date, urgency status, and can be assigned to a specific category. Categories can be created independently in the Category tab.

The live link can be found here: https://kizzy-taskmanager.herokuapp.com/

## Features

- Create tasks with the following details:
  - Task Name
  - Description
  - Due Date
  - Urgency (Mark as urgent or not)
  - Assign to a Category

- Edit tasks to update any of the fields, including changing the category.

- Delete tasks that are no longer needed.

- Create and manage task categories.

## Usage

### Creating a Category:

- Navigate to the "Category" tab.
- Add a new category (e.g., Work Category, Holiday Category).

### Creating a Task:

- Navigate to the "Add Task" tab.
- Fill in the task details:
  - Task Name
  - Description
  - Due Date
  - Urgency (Check if urgent)
  - Assign to a Category (Select from existing categories)

### Editing a Task:

- Navigate to the "Tasks" tab.
- Find the task you want to edit and click on the "Edit" button.
- Modify the task details as needed.

### Deleting a Task:

- Navigate to the "Tasks" tab.
- Find the task you want to delete and click on the "Delete" button.

## Deployment

This application is deployed on Heroku. Follow these generic steps to deploy the app:

1. **Create a Heroku Account:**
   - If you don't have a Heroku account, [sign up for free](https://signup.heroku.com/).

2. **Install Heroku CLI:**
   - Download and install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).

3. **Login to Heroku:**
   - Open a terminal and run `heroku login` to log in to your Heroku account.

4. **Create a Heroku App:**
   - Run `heroku create` in the terminal within your project directory.

5. **Configure Environment Variables:**
   - Set the necessary environment variables on your Heroku app, including database credentials and any other configuration required.

6. **Deploy the App:**
   - Commit any changes to your Git repository.
   - Run `git push heroku master` to deploy your app to Heroku.

7. **Open the App:**
   - Once the deployment is successful, run `heroku open` to open the app in your default web browser.

## Disclaimer

This project was developed as part of a course and served as a walkthrough/code-along project to learn and demonstrate the functionality of Flask and SQLAlchemy. I want to make it clear that not all the code is original, and I do not claim it as my own work. The purpose of this project is educational, showcasing the implementation of certain technologies under the guidance of the course material.
