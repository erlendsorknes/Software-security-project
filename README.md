# Software Security Project 2024

Project for the course Software Security 2024 at Universita degli Studi di Napoli Federico II.

The project is based on the OWASP NodeGoat project, a deliberately insecure web application used to teach web application security. The project is a Node.js web application that contains a tutorial page that explains the OWASP Top 10 vulnerabilities and how to fix them.

##### Default user accounts

The database comes pre-populated with these user accounts created as part of the seed data -
* Admin Account - u:`admin` p:`Admin_123`
* User Accounts (u:`user1` p:`User1_123`), (u:`user2` p:`User2_123`)
* New users can also be added using the sign-up page.


## Run Project using Docker

The repo includes the Dockerfile and docker-compose.yml necessary to set up the app and db instance, then connect them together.

1) Install [docker](https://docs.docker.com/installation/) and [docker compose](https://docs.docker.com/compose/install/) 

2) Clone the github repository:
   ```
   git clone https://github.com/erlendsorknes/Software-security-project.git
   ```

3) Go to the directory:
   ```
   cd Software-security-project
   ```

4) Build the images:
   ```
   docker-compose build
   ```

5) Run the app, this starts the NodeGoat application at http://localhost:4000/:
   ```
   docker-compose up
   ```


## Contributors

Erlend Sorknes and Thomas Wikestad Melkeraaen

