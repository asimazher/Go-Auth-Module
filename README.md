# Go-Auth-Module

Golang Auth Module

This project demonstrates how to implement authentication using various OAuth providers in a Golang application.

Setup:


Clone the repository:

git clone <repository-url>


Install dependencies:


go mod tidy


Create a .env file in the project root and specify your OAuth provider keys and secrets:


FACEBOOK_KEY=<your-facebook-key>

FACEBOOK_SECRET=<your-facebook-secret>

GOOGLE_KEY=<your-google-key>

GOOGLE_SECRET=<your-google-secret>



Run the application:


go run main.go



OAuth Providers:

Facebook
Google



Usage:

Visit http://localhost:3000 in your browser.

Click on the respective OAuth provider link to log in.


Upon successful authentication, user details will be displayed.


Project Structure:


main.go: Contains the main application logic and server setup.

providers/: Contains OAuth provider configurations.

templates/: Contains HTML templates for rendering user interfaces.

services/: Contains services for handling user authentication and authorization.


Dependencies:


gorilla/pat: A Sinatra-style pattern muxer for Go's net/http library.

joho/godotenv: Loads environment variables from a .env file.

markbates/goth: OAuth, OAuth2, and OpenID Connect client library for Go.
