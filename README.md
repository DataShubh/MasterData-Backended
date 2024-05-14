# Master-Data Backend using Python, Flask, and MongoDB

This repository contains the backend code for managing master data related to webinars, speakers, and viewing order details. It's built using Python, Flask, and MongoDB, and deployed on Azure.

## Utility

The backend provides the following functionalities:

1. Webinars Management: Allows creating, updating, deleting, and retrieving details of webinars. This includes information such as webinar title, description, date, and duration.

2. Speakers Management: Provides CRUD operations for managing speakers. Speaker details such as name, bio, and contact information can be stored and modified.

3. Viewing Order Details: Stores and manages viewing order details, including user information, webinar details, and viewing history.

## Technologies Used

- **Python:** Backend logic is implemented using Python, a versatile and widely-used programming language.
- **Flask:** Flask is used as the web framework to build the RESTful APIs for managing data.
- **MongoDB:** MongoDB serves as the database for storing master data related to webinars, speakers, and viewing orders.
- **Azure:** The application is deployed on the Azure cloud platform, ensuring scalability and reliability.

## Getting Started

To get started with the backend development, follow these steps:

1. **Clone the Repository:**
   
2. **Install Dependencies:**
   
3. **Set Up MongoDB:**
- Install MongoDB on your local machine or set up a MongoDB instance on Azure.
- Update the MongoDB connection URI in the Flask application configuration.

4. **Run the Application:**

The backend server should now be running locally. You can make HTTP requests to the defined endpoints to interact with the master data.

## API Endpoints

The backend exposes the following API endpoints:

- `/webinar_panel`: CRUD operations for managing webinars.
- `/speaker_panel`: CRUD operations for managing speakers.
- `/order_panel`: Operations for managing viewing orders and viewing history.

Refer to the API documentation or the codebase for detailed information about each endpoint.

## Deployment

The application is deployed on Azure, ensuring availability and scalability. Continuous integration and deployment pipelines can be set up to automate the deployment process.

## Contributing

Contributions are welcome! If you have suggestions, feature requests, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


