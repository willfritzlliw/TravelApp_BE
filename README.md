# TravelApp BE

TravelApp BE is the backend for a travel application that provides a RESTful API for managing users, groups, and travel-related data.

## Features

*   User authentication and authorization
*   API endpoints for users and groups
*   Scalable architecture using Django and Django Rest Framework

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Python 3.8+
*   Pip
*   Virtualenv

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/your_username/TravelApp_BE.git
    ```
2.  Create a virtual environment
    ```sh
    python -m venv venv
    ```
3.  Activate the virtual environment
    ```sh
    # Windows
    venv\Scripts\activate
    # Mac/Linux
    source venv/bin/activate
    ```
4.  Install dependencies
    ```sh
    pip install -r requirements.txt
    ```
5.  Run migrations
    ```sh
    python manage.py migrate
    ```
6.  Start the development server
    ```sh
    python manage.py runserver
    ```

## Usage

The API can be accessed at `http://127.0.0.1:8000/`.

## API Endpoints

The following API endpoints are available:

*   `/users/`: GET, POST
*   `/users/<id>/`: GET, PUT, DELETE
*   `/groups/`: GET, POST
*   `/groups/<id>/`: GET, PUT, DELETE

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
