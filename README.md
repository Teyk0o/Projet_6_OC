# Snowboard Tricks Community Site Installation Guide 🏂

Welcome to the installation guide for the Snowboard Tricks Community Site! This README will guide you through setting up the project using Wamp (Windows) or Mamp (MacOS). Let's get started! 🚀

## Prerequisites
- Wamp Server for Windows or Mamp Server for MacOS
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Composer
- Git

## Installation Steps

### Step 1: Set Up Your Local Server
- Download and install Wamp Server from [here](https://www.wampserver.com/en/) if you are on Windows.
- For MacOS, download and install Mamp from [this link](https://www.mamp.info/en/).

### Step 2: Clone the Repository
- Clone the project repository using Git: ```git clone https://github.com/Teyk0o/Projet_6_OC.git```

### Step 3: Configure Your Environment
- Navigate to your project directory: ```cd Projet_6_OC```
- Install dependencies using Composer: ```composer install```

### Step 4: Set Up the Database
- Create a new MySQL database via phpMyAdmin in Wamp/Mamp.
- Configure your `.env` file with the correct database connection details.

### Step 5: Run Migrations
- Run migrations to set up your database schema: ```php bin/console doctrine:migrations:migrate```

### Step 6: Start the Server
- Start the Symfony server: ```symfony server:start```

## Development Checklist 📋

- [x] **Step 1**: Fully understand the project specifications and detailed requirements.
- [ ] **Step 2**: Produce UML diagrams (data model, classes, sequences, use cases).
- [x] **Step 3**: Create the GitHub repository for the project.
- [x] **Step 4**: Create all issues on the GitHub repository ([here](https://github.com/Teyk0o/Projet_6_OC/issues/new)).
- [x] **Step 5**: Estimate all your issues.
- [ ] **Step 6**: Start developing the application and propose pull requests for each feature/issue.
- [ ] **Step 7**: Have your mentor review your code (proposed in pull requests), and once approved, merge the pull requests into the main branch.
- [ ] **Step 8**: Perform a demonstration of the entire application.
- [ ] **Step 9**: Prepare all your deliverables and submit them on the platform.

## Conclusion
Congratulations! You should now have a running local version of the Snowboard Tricks Community Site. Happy coding! 💻
