
# Authentication Backend

Backend for the Authentication

# Setup
Install nodejs and mysql.

# Create database

node_modules/.bin/sequelize db:create

# Migrate db to the running service

npm run migrate

# Set the following variables in a file called `.env` at the project root:

MYSQL_HOST=
MYSQL_DATABASE=
MYSQL_USERNAME=
MYSQL_PASSWORD=
MAILGUN_PUBLIC=
MAILGUN_PRIVATE=
FRONTEND_BASE_URL=

# Start the server:

npm run start:dev

# Start frontend

# install npm
npm install

# start

npm start