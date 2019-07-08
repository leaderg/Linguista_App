# Linguista

Linguista is a web application designed to help with learning languages. Utilizing ePub files in a foreign language, you're able to read along and instantaneously translate words you don't understand into english.

# SET UP THE DATABASE

To set up database:
  1. In terminal go to the express-back-end folder.
  2. Run `psql` in the terminal.
  3. Run `create database linguista;`
  4. Run `\c linguista`
  5. Run `\i db/linguista.sql`.

Tables should be created locally for your server instance.

## User Stories
- "As a user, I want to improve my french comprehension skills."
- "I want to upload my own Epub docs and read my book in a reader. If I don't understand a word, I want to be able to click on it and see the translation pop-up while also adding that word into a library to review later"
- " I want to be able to review trouble words at my leisure later on and rank them based on difficulty"

## Running the project

You need **TWO** terminals for this.

In one terminal, `cd` into `react-front-end`. Run `npm install` or `yarn` to install the dependencies. Then run `npm start` or `yarn start`, and go to `localhost:3000` in your browser.

In the other terminal, `cd` into `express-back-end`. Run `npm install` or `yarn` to install the dependencies, then `npm start` or `yarn start` to launch the server.

In the browser, you can click on the button and see the data get loaded.

If this doesn't work, please message me!

