# Shell-Scripting-project-to-list-users-in-organizations.

## Description
🔍 This Shell Script project is designed to list the collaborators (users with access) in GitHub organizations. It utilizes the GitHub API to fetch and display the list of users with read access to specified repositories within an organization.

## Features

✔️ Retrieve and display users with read access to specified repositories within an organization.

✔️ Easy-to-use command-line interface.

✔️ Customizable script parameters for different organizations and repositories.

✔️ Automated error handling for incorrect input and API requests.

Installation
1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Geetika563/Shell-Scripting-project-to-list-users-in-organizations.git
2. Navigate to the project directory:

   ```bash
   cd Shell-Scripting-project-to-list-users-in-organizations
4. Ensure that you have the required dependencies installed:

  - Bash (v4.0 or higher)
  - cURL
  - jq (for JSON parsing)
5. Usage
Run the script with the following command:

  ```bash
  ./list-users.sh <organization_name> <repository_name>
