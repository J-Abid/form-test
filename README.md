# form-test #
**Test form email template - Made by Junaid Abid**

Contact Form Backend Integration Tests

This repository serves as a proof-of-concept project to evaluate different serverless form backend providers for a static portfolio website. The goal was to implement, test, and compare the reliability of Web3Forms and Formspree before selecting a final solution for production.

Project Structure & File Descriptions

This project consists of three main components designed to isolate and test specific API functionalities:

1. index.html (The Testing Hub)

This is the main entry point for the GitHub Pages deployment. It acts as a central navigation hub, allowing users to choose which backend service they wish to test.

Function: Provides a clean UI to switch between the Web3Forms and Formspree implementations without needing to manually change URLs.

Tech: HTML5, CSS3 (Internal styling for responsive buttons).

2. index-web3forms.html (Web3Forms Implementation)

A standalone test unit for the Web3Forms API.

Key Features:

Integration via public Access Key.

Tests input validation and API response latency.

Verifies email delivery without server-side code.

3. index-formspree.html (Formspree Implementation)

A standalone test unit for the Formspree API.

Key Features:

Integration via unique Form Endpoint.

Tests standard POST submission flow.

Evaluates spam filtering and submission dashboard connectivity.

Live Demo: You can test the live implementations here: https://j-abid.github.io/form-test/

Technologies Used

Frontend: HTML5, CSS3

Backend Services: Web3Forms API, Formspree API

Deployment: GitHub Pages
