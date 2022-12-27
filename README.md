# Currently's Server

## How to install

- Open terminal and go into your workspace
- run this command: 'git clone https://github.com/kevinmlee/social-search-server.git'
  - it should start downloading everything you need.
- run 'npm install' in the root direction to install required dependencies for the server

## Running your local dev environment
- In your terminal, starting from the root of the project, type in 'npm start'

## Pushing to staging

- Set up your branch with 'git checkout -b your-name/issue-#'
- Once you are statisfied with your changes, run 'git add --all' in terminal
- Run "git commit -m 'your explanation of your changes'" (without the double quotes).
  - Please make sure this is short, but descriptive.
  - For example: "Fixed bug" is not enough. "Fixed bug causing page component to crash. Updated blah function." is descriptive.
- Run 'git push'
- Go to github and submit a pull request

## Getting your changes onto production

- Your changes will need to be reviewed before it will be pushed into the production environment so this process may take some time as it will be manually reviewed

## Todo
- Create tests locally and on GitHub Actions
- Set up CI/CD to run tests and automatically deploy once merged
