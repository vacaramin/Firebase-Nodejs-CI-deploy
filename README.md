# Firebase CI/CD Demo for Node.js App

This repository serves as a demonstration of setting up a continuous integration (CI) and continuous deployment (CD) pipeline for a Node.js application deployed on Firebase.

## Overview

The project contains a simple Node.js application created using `create-react-app`. It includes configurations for automating the CI/CD process using Firebase Hosting and GitHub Actions.

## CI/CD Pipeline

The CI/CD pipeline is configured using GitHub Actions. Whenever changes are pushed to the `main` branch, the following steps are executed:

1. **Build:** The Node.js application is built using `npm run build`.

2. **Test:** Unit tests (if included) are executed to ensure code quality.

3. **Deploy:** The built artifacts are deployed to Firebase Hosting.