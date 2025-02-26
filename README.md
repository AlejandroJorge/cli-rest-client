# Api Rester

A lightweight command-line REST client for testing APIs without the overhead of GUI applications like Postman or Insomnia.

## Features Plan

1. Request Execution
    1.1 Read a `request.json` which includes metadata (host, headers, path) and body [DONE]
    1.2 Execute HTTP Request logging request information
    1.3 Write the `response.json` with metadata and body [DONE]
2. Support environment variables to be replaced in `request.json` files (`{{API KEY}}`)
3. Custom files workflow (request and response object to be defined with command line)
4. Validate `request.json` schema
5. Error handling (timeouts, network errors, invalid JSON, etc)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
