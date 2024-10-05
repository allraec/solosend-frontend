# SoloSend Frontend
This is the frontend for **SoloSend**, an invoicing app designed for freelancers. The frontend is built using **Angular** and interacts with a **Node.js** backend for user registration and login functionalities.

## Project Setup
### 1. Fork and Clone the Repository
First, fork the repository to your GitHub account by clicking the "Fork" button at the top right of the project repository page. Then, clone your forked repository to your local machine:
```
git clone https://github.com/yourusername/solosend-frontend.git
cd solosend-frontend
```
### 2. Install Dependencies
Once inside the project directory, install the necessary dependencies:
```
npm install
```
### 3. Run the App Locally
After installing dependencies and setting up the environment, start the development server:
```
ng serve
```
Open your browser and go to http://localhost:4200 to view the app.
## Features
- User Registration: A simple registration form that allows users to create an account.
- User Login: A login form to authenticate users.
- Integration with Backend: The app communicates with the backend via REST APIs for user registration and login.
## Tech Stack
- Angular: Frontend framework
- TypeScript: Primary language used
- SCSS: Styling
- REST API: Communicates with the backend.
## Contributing
We welcome contributions! Please follow these steps to contribute to the project:
### 1. Create a new branch
Branch names should follow this format:
```
git checkout -b feature/short-description
```
Example:
```
git checkout -b feature/add-login-page
```
### 2. Make your changes and stage them:
```
git add .
```
### 3. Commit your changes
```
git commit -m "Add feature description"
```
### 4. Push to your fork
```
git push origin feature/short-description
```
### 5. Submit a pull request
Once you submit your pull request, we will review it and merge it if everything looks good.

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
