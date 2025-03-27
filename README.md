# Recipe Web Application

## Overview
The Recipe Web Application is a full-stack web application that allows users to create, manage, and share recipes. It provides features such as user authentication, recipe categorization, and view tracking.

## Features
- **User Registration & Authentication**: Secure user sign-up, login, and logout.
- **Recipe Management**: Users can create, edit, delete, and organize recipes.
- **Categorization**: Recipes can be categorized.
- **View Tracking**: Track the number of times a recipe has been viewed.
- **RESTful API Endpoints**: Provides API support for integration with other applications.
- **Comments & Ratings**: Users can comment on and rate recipes.
- **Search & Filter**: Users can search and filter recipes based on categories or ingredients.

## Installation & Setup
### Prerequisites
- [Scala](https://www.scala-lang.org/)
- [Play Framework](https://www.playframework.com/)
- [sbt (Scala Build Tool)](https://www.scala-sbt.org/)
- Database: PostgreSQL or MongoDB
- Git

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/D98amian/recipe-web-app.git
   cd recipe-web-app
   ```
2. Install dependencies and run the application:
   ```sh
   sbt run
   ```
3. Open the application in the browser at `http://localhost:9000/`

## Technologies Used
- **Backend**: Scala (Play Framework)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: PostgreSQL
- **Authentication**: JWT / OAuth
- **DevOps**: GitHub, Docker (optional for deployment)

## API Documentation
- API endpoints follow RESTful conventions.
- Swagger or Postman collection will be provided.

## Deployment
To deploy the application:
1. Set up a cloud server (Heroku, AWS, or DigitalOcean).
2. Configure the database connection in `application.conf`.
3. Deploy using Docker or a cloud provider's CLI.

## Contributing
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit changes and push to your fork.
4. Open a pull request.

## License
This project is licensed under the MIT License.

