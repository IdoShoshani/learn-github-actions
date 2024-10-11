# Learn GitHub Actions

This repository is designed to help you learn and practice GitHub Actions through a series of hands-on tasks.

## What are GitHub Actions?

GitHub Actions is a powerful automation tool that allows you to define custom workflows for your GitHub repositories. These workflows can automatically run commands or scripts in response to specific events, such as pushing code, creating issues, or on a scheduled basis. This enables you to implement continuous integration, automated testing, and various other tasks directly within your GitHub repository.

## Repository Contents

This repository contains a series of tasks designed to help you learn different aspects of GitHub Actions. Each task focuses on a specific feature or use case, allowing you to gradually build your understanding and skills.

## Tasks

1. **Setting Up a Simple Workflow**

   - Create a basic GitHub Action that runs a simple "Hello, World!" script every time code is pushed to the repository.

2. **Running a Workflow on a Schedule**

   - Create a GitHub Action that runs a simple script (like "echo 'Hello!'") at a specific time every day.

3. **Sending a Notification for Every Push**

   - Set up a GitHub Action that sends an email notification to yourself every time code is pushed to the repository.

4. **Running a Simple Math Calculation**

   - Set up a GitHub Action that runs a basic calculation (e.g., echo $((2 + 2))) and logs the result.

5. **Notifying on Issue Creation**

   - Set up a workflow to send a notification every time a new issue is created.

6. **Logging the Username of the Committer**

   - Set up a GitHub Action that logs the GitHub username of the person who made the latest commit.

7. **Automated Code Linting**

   - Set up a GitHub Action to automatically run a linter for Python.

8. **Running Unit Tests on Push**

   - Configure a GitHub Action to run unit tests using a testing framework (use pytest for Python).

9. **Building and Testing a Docker Image**

   - Create a workflow that builds a Docker image and runs tests on it when code is pushed to the main branch.

10. **Deploying to GitHub Pages**

    - Configure a GitHub Action to deploy a static website to GitHub Pages on every push to the main branch.

11. **Automating Greetings on Issues**

    - Create a workflow that automatically posts a welcome message whenever a new issue is created in the repository.

12. **Daily Repository Cleanup**
    - Set up a scheduled workflow that runs daily to delete unnecessary branches that have been merged or to remove old logs.

## Getting Started

To get started with these tasks:

1. Clone this repository to your local machine.
2. Create a new branch for each task.
3. Implement the GitHub Action for the task.
4. Test your implementation.
5. Push your changes and create a pull request.

Happy learning!
