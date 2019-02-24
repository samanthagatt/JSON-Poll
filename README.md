# JSON Poll

## Base URL
- "localhost:8080/api"

## Endpoints
- `"/list"` (`GET`)
    - Responsible for fetching all polls available for voting
    - Returns JSON array of poll information
    - Example Response:

    ```JSON

    ```

- `/create"` (`POST`)
    - Creates a new poll
    - Requires a poll title and at least two voting options
    - Example request body in JSON:

    ```JSON

    ```

- `/vote/{pollid}/{option}` (`POST`)
    - Casts a vote for a specified poll
    - Example URL request:
        `localhost:8080/api/vote/3532/2`

## Starting Vapor Template

A template for Vapor 3 users that does the absolute minimum to set up a working Vapor 3 environment.

If you have already installed the Vapor toolbox, you can create a new Vapor project using the following bash command: 
    `vapor new <MyProject> --template=twostraws/vapor-clean`
