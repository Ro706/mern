
# MERN Stack Application

## Description
This is a MERN (MongoDB, Express.js, React, Node.js) stack application designed as an employee management system. 

## Latest Commit
The latest commit on the main branch was made by [Ro706](https://github.com/Ro706) with the message: "v.1.2 backend & client site (employee management system)". You can view the commit [here](https://github.com/Ro706/mern/commit/d5d246e58ccd632fda5e266ccaa0a795afa289e6).

## Contributors
- [Ro706](https://github.com/Ro706) (4 contributions)

## Installation
To install and set up the project, follow these steps:

# linux User: 
1. Clone the repository:
    ```bash
    apt install git
    git clone https://github.com/Ro706/mern.git
    cd mern
    ```
1. Clone the repository:
    ```bash
    git clone https://github.com/Ro706/mern.git
    cd mern
    ```

2. Install the dependencies:
    ```bash
    cd server
    npm i
    cd ..
    cd client
    npm i
    ```

3. Set up the environment variables.
server/config.env
```bash
ATLAS_URI="YOUR KEY"
PORT=5050
```

5. Start the development server:
    ```bash
     node --env-file=config.env server
    ```
6. Start the development Client
   ```bash
    npm run dev
   ```
## Usage
After setting up, you can run the application locally by navigating to ` http://localhost:5173/`.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License.
