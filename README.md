# Todo Application

This is a simple Todo application with both frontend and backend. You can run this project either directly on your machine or using Docker.

## Prerequisites
- Node.js (https://nodejs.org/)
- Docker (https://www.docker.com/) (if you plan to use Docker)
- A running instance of MongoDB (if you donot plan to use Docker)
- Make sure that port 3000, 5000, and 27017 are not used by any application. If you are planning to run without Docker, port 27017 should be used MongoDB.
- Moesif CORS extension for Google Chrome (https://chrome.google.com/webstore/detail/moesif-origin-cors-change/digfbfaphojjndkpccljibejjbppifbc) 

## Setup

### Running on your machine

1. Navigate to both `todo-api` and `todo-app` directories in separate terminal windows.

2. In each directory, run `npm install` to install necessary dependencies.

3. In the `todo-api` directory, start the backend server with `npm start`.

4. In the `todo-app` directory, start the frontend with `npm start`.

5. Ensure the Moesif CORS extension is installed and enabled in your Google Chrome browser.

6. Open `http://localhost:3000` in Google Chrome to view the application.

### Running with Docker

1. Ensure Docker is installed on your machine.

2. Navigate to the root project directory in your terminal.

3. Run `docker-compose up`.

4. Once Docker reports that the application is running, open `http://localhost:3000` in Google Chrome to view the application.

## Usage

Add your tasks and manage them with this simple Todo application. You can mark tasks as completed, delete them, or add new ones. Enjoy!

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
