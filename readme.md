# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker if you haven't already

2. Verify that docker is installed by running `docker -v` and `docker-compose -v`

3. Clone this repository:

    ```bash
    git clone https://github.com/ObelusFamily/Anythink-Market-czvq9.git
    ```
4. `docker-compose up`

5. When docker has finished building the containers, run:

    ```bash
    curl http://localhost:3000/api/ping
    ```

    to verify that the backend is working properly.

6. Visit https://localhost:3001/register in your browser.
