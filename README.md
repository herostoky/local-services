# Local Development Services

This repository contains a Docker Compose file for setting up local development services, including MySQL, PostgreSQL, MongoDB, Seq, and more.

## Table of Contents

- Services
- Getting Started
- Usage
- Contributing
- License

## Services

The following services are included in the Docker Compose file:

- **MySQL**: A popular relational database management system.
- **PostgreSQL**: An advanced, open-source relational database.
- **MongoDB**: A NoSQL database known for its flexibility and scalability.
- **Seq**: A log server for structured log data.

## Getting Started

To get started with these services, follow the steps below:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Start the services**:
    ```sh
    docker-compose up -d
    ```

3. **Verify the services**:
    - MySQL: `localhost:3306`
    - PostgreSQL: `localhost:5432`
    - MongoDB: `localhost:27017`
    - Seq: `localhost:5341`

## Usage

- **MySQL**:
    ```sh
    mysql -h localhost -P 3306 -u root -p
    ```

- **PostgreSQL**:
    ```sh
    psql -h localhost -p 5432 -U postgres
    ```

- **MongoDB**:
    ```sh
    mongo --host localhost --port 27017
    ```

- **Seq**:
    Open your browser and navigate to `http://localhost:5341`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
