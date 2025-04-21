# TaskNest - Task Management Application

A comprehensive, user-friendly task management web application that allows you to manage your daily tasks efficiently, schedule tasks, and receive email reminders.

## Features

- Add new tasks to your to-do list
- Mark tasks as completed with a click
- Delete tasks you no longer need
- User authentication (sign up/sign in)
- Task scheduling with date and time
- Email reminders for scheduled tasks
- Data persistence using browser's localStorage
- Clean and responsive user interface
- Simple and intuitive design

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- LocalStorage API for data persistence
- EmailJS for email notifications
- Deployed on Vercel

## Screenshot

![TaskNest App](icon.png)

## Usage

1. Sign up for a new account or sign in if you already have one
2. Enter your task in the input field
3. Click the "Add" button to add the task to your list
4. Click on a task to mark it as completed
5. Click on the "×" symbol to delete a task
6. Use the "Schedule Tasks" section to create tasks with specific dates and times
7. Set email reminders for your scheduled tasks
8. Receive email notifications before your scheduled tasks

## Email Reminder Feature

TaskNest uses EmailJS to send reminder emails for scheduled tasks. You can choose to be notified 5, 10, 15, 30, or 60 minutes before a task is due.

## How to Run Locally

Simply open the `index.html` file in your web browser to run the application.

```bash
# If you have a local server like Live Server extension in VS Code, you can use:
# Right-click on index.html and select "Open with Live Server"

# Alternatively, you can use any web server to serve these files
```

## Project Structure

- `index.html` - The main HTML structure
- `signin.html` - User sign in page
- `signup.html` - User registration page
- `style.css` - All styling rules
- `script.js` - JavaScript functionality
- `checked.png` - Icon for completed tasks
- `unchecked.png` - Icon for pending tasks
- `icon.png` - Application icon
- `logo2.png` - TaskNest logo

## Deployment

The application is deployed on Vercel. Visit [TaskNest App](https://tasknest-green.vercel.app/) to use the application.

## License

This project is open source and available for personal and educational use. 
