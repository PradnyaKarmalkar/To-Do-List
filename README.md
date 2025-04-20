# TaskNest - To-Do List & Task Scheduler

A comprehensive task management web application that allows users to create to-do lists and schedule tasks with email reminders.

## Features

- User authentication (sign up and sign in)
- Add new tasks to your to-do list
- Mark tasks as completed with a click
- Delete tasks you no longer need
- Schedule tasks with specific date and time
- Email reminders for scheduled tasks
- Customizable reminder times (5, 10, 15, 30 minutes, or 1 hour before)
- Data persistence using browser's localStorage
- Clean and responsive user interface
- Simple and intuitive design

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- EmailJS for email notifications
- LocalStorage API for data persistence
- Browser Notifications API

## Screenshot

![TaskNest App](icon.png)

## Usage

### To-Do List
1. Enter your task in the input field
2. Click the "Add" button to add the task to your list
3. Click on a task to mark it as completed
4. Click on the "×" symbol to delete a task

### Task Scheduling
1. Sign in or sign up to access the scheduling feature
2. Enter the task name and select a date and time
3. Choose how early you want to receive an email reminder
4. Click "Schedule Task" to add it to your scheduled tasks
5. Receive email reminders before your scheduled tasks

## Deployment on Vercel

This application is configured for easy deployment on Vercel:

1. **Sign up for Vercel**
   - Visit [vercel.com](https://vercel.com) and create an account if you don't have one

2. **Install Vercel CLI** (optional)
   ```bash
   npm i -g vercel
   ```

3. **Deploy using Git integration**
   - Connect your GitHub/GitLab/Bitbucket repository
   - Import your TaskNest repository
   - Vercel will automatically detect the configuration
   - Click Deploy

4. **Alternative: Deploy using Vercel CLI**
   ```bash
   # Login to Vercel
   vercel login

   # Navigate to your project directory
   cd path/to/tasknest

   # Deploy
   vercel
   ```

5. **Environment Variables**
   - Vercel will use the environment variables defined in vercel.json
   - You can also configure them in the Vercel dashboard under Settings > Environment Variables

## Project Structure

- `index.html` - The main application
- `signin.html` - User sign-in page
- `signup.html` - User registration page
- `style.css` - All styling rules
- `script.js` - JavaScript functionality for the to-do list
- `.env` - Environment variables for local development
- `vercel.json` - Vercel deployment configuration

## EmailJS Configuration

This project uses EmailJS for sending email reminders:

1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Create an email service and template
3. Update the service ID and template ID in the .env file and vercel.json

## License

This project is open source and available for personal and educational use. 