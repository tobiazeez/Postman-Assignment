Postman and GitHub Integration Assignment

## Overview
This repository contains the assignment for integrating Postman with GitHub and setting up CI/CD processes.

## Steps Followed
1. **Postman Collection and Tests**
   - Imported the Library API Reference collection into Postman.
   - Added automated tests for each request:
     - **GET /books**: Tested for status code, response time, and response format.
     - **GET /book**: Tested for status code and response structure.
     - **POST /add book**: Tested for status code and response properties.
     - **PATCH /update book**: Tested for status code and updated information.
     - **DELETE /delete book**: Tested for status code.

2. **GitHub Repository Setup**
   - Created a GitHub repository named `postman-assignment`.
   - Created `dev` and `master` branches.

3. **Connecting Postman to GitHub**
   - Exported the Postman collection as a JSON file.
   - Added the JSON file to the GitHub repository and synced it with the `dev` branch.

4. **Demonstrating Changes**
   - Made changes in Postman, exported the updated collection, and pushed it to the `dev` branch.
   - Created a Pull Request (PR) to merge `dev` into `master`.

5. **CI Tool Comparison**
   Comparing Jenkins with GitHub Actions.
     
     Jenkins Advantages:
     - Highly customizable with numerous plugins.
     - Open-source and free to use.
     - Strong community support.
     - Supports a wide range of languages and tools.
    
       Jenkins Disadvantages:
     - Requires dedicated infrastructure & maintenance.
     - Steeper learning curve for initial setup.
     - Configuration can be complex.
    
       GitHub Actions Advantages:
     - Integrated with GitHub, making it easy to use with GitHub repositories.
     - Simple YAML configuration.
     - Managed infrastructure reduces maintenance.
     - Supports a wide range of actions and integrations.
  
       GitHub Actions Disadvantages:
     - Limited to GitHub repositories.
     - Potential limitations for complex workflows compred to Jenkins.

## How to View the Assignment
1. Clone the repository: `git clone https://github.com/yourusername/postman-assignment.git`
