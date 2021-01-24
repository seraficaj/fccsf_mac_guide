# Databases, Languages, and Frameworks

## Node.js, NPM, and NVM

Node is a JavaScrpit engine used for back-end and full-stack web development. This is an essential installation for freeCodeCamp's curriculum and beyond.

`brew install node`

Verify th einstallation afterwards by running:
```
node -v
npm -v
```

Install nodemon globally. This useful package automates starting a node server in many projects.

`npm install -g nodemon`

## PostgreSQL

Install PostgreSQL (AKA Postgres) with brew:
`brew install postgresql`

After postgresql is installed, run this command to start postgres server:
`brew services start postgresql`

## MongoDB

Install MongoDB with brew:
`brew tap mongodb/brew`
The above command may take a while to complete. When it finishes, continue the installation:
`brew intsall mongodb-community`

To start the MongoDB server, run this command:
`brew services start mongodb-community`

## Python 3
Install Python3 with brew:
`brew install python`

Check your computer has Python3:
`python3 --version`

pip3, a package manager for Python3 should have also been installed.
`pip3 --version`

## Django
Install Django using pip3:
`pip3 --version`

If you receive a permissions error, try running this instead:
`pip3 install --user Django`

## Heroku CLI for Deployment

run: `brew tap heroku/brew && brew install heroku` 

then, confirm installation with `heroku open` or `heroku apps`

## Next steps...
* [X] [Command Line](command-line-setup.md)
* [X] [Installing Git](git-installation.md)
* [X] [Databases and Frameworks](db-frameworks.md)
* [ ] [Desktop Applications](desktop-applications.md)