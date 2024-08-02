 
# What ToDo

## A ToDo app

Practice project creating a todo list app that will have an node express server working with a postgres database linked up to a frontend that will allow a user to add/remove and track to do items

### To Install

Run the command `npm install`
This will install all the project dependencies

You will need your own Postgres database to store records in. There are many options for this but a quick and free way to get up and running would be to use Render to create a Postgres DB

You will also need to create a `.env` file with at least 2 entries in it:
`DB_CONNECTION_STRING = ` - Enter your database connection string here
`PORT = ` - Choose a port to access the app on

### To run

The command `npm run dev` will start the app listening on the port you've specified above