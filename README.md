
**Footfab**

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Footfab is a comprehensive footwear recommendation system designed to help users discover their perfect pair of shoes. This project consists of two main components - the backend ([Footfab-back](https://github.com/tandemresistentia/Footfab-back)) and the frontend ([Footfab-front](https://github.com/tandemresistentia/Footfab-front)).

- The **[Footfab-back](https://github.com/tandemresistentia/Footfab-back)** repository contains the backend component built using Django, a high-level Python web framework. It is responsible for handling data processing, user interactions, and providing the necessary functionalities to the frontend application.

- The **[Footfab-front](https://github.com/tandemresistentia/Footfab-front)** repository contains the frontend component responsible for the user interface and interactions. It is developed using modern web technologies like React, JavaScript, and CSS.

By combining both the backend and frontend components, Footfab offers a personalized and interactive shoe shopping experience by leveraging machine learning algorithms to analyze user preferences and historical data to make accurate footwear recommendations.

## Features

- User authentication and registration
- Shoe recommendation based on user preferences
- Filtering and sorting of shoe options
- User feedback collection to improve recommendations
- CRUD operations for shoes, user profiles, and feedback data

## Installation

To run Footfab locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/tandemresistentia/Footfab.git
   ```

2. Navigate to the project directory:

   ```
   cd Footfab
   ```

3. Install the Python and Node.js dependencies:

   ```
   pip install -r requirements.txt
   cd frontend
   npm install
   ```

4. Set up the necessary environment variables (database connection, API keys, etc.).

5. Run the Django development server:

   ```
   python manage.py runserver
   ```

6. Start the React development server:

   ```
   cd frontend
   npm start
   ```

## Usage

Once both the backend and frontend servers are up and running, the Footfab application will be accessible through the web browser. Users can sign up, log in, and begin exploring shoe recommendations based on their preferences. The frontend application interacts with the backend API endpoints to fetch shoe recommendations, process user feedback, and perform various other functionalities.

For detailed API documentation of the backend, refer to the [API Documentation](https://example.com/footfab-back/api-docs) section in the Footfab-back repository.

## Technologies Used

- Django (Backend)
- Python (Backend)
- Django REST framework (if applicable)
- React (Frontend)
- JavaScript (Frontend)
- CSS (Frontend)
- MongoDB (if applicable)
- JWT (JSON Web Tokens) for authentication (if applicable)
- Machine Learning algorithms (Details to be specified if applicable)

## Contributing

Contributions to Footfab are welcome and encouraged. If you find any bugs, want to propose new features, or wish to improve the existing codebase, please create a pull request. Be sure to follow the project's code of conduct.

## License

[MIT License](https://github.com/tandemresistentia/Footfab/blob/main/LICENSE)

---

