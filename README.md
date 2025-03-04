# GitHub-Actions-CI-CD-Setup

This application takes starter code and creates a CI/CD pipeline using GitHub Actions to run the component tests via Cypress when a Pull Request is made to the develop branch, and the application is deployed when code is merged from develop to the main branch.

## User Story

```
AS A software engineer looking to integrate a CI/CD pipeline in a codebase
I WANT a full-stack application that runs test cases when a Pull Request is made to the develop branch and automatically deploys to Render when the code is merged to main
SO THAT I can ensure that all code integrations are clean and pass the proper requirements and that the application is constantly updated when major releases are made to the main branch
```

## Technologies

The GitHub repository has both a main branch, a develop branch, and use feature branches to submit Pull Requests.

A GitHub Action triggers when a Pull Request is submitted to a develop branch and the Action must execute the Cypress component tests.

All Cypress component tests pass.

A GitHub Action triggers when a Pull Request is submitted and merged to the main branch and the Action must automatically deploy the application to Render.

The application is deployed to Render.

## References

I had some help with bootcamp course info, chatGPT, and stackoverflow

## GitHub and Video

```
https://github.com/CourtneyPonder/GitHub-Actions-CI-CD-Setup
```
