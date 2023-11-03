# Todo List Application - Backend (Hexagonal Architecture)

This is the backend component of the Todo List application, built using Nest.js and designed upon the robust and modular Hexagonal Architecture for enhanced scalability and maintainability.

## Overview

The backend part of the Todo List application is developed with Nest.js, a powerful Node.js framework, following the principles of the Hexagonal Architecture. This architecture separates the application into distinct layers, allowing for better organization, maintainability, and adaptability.

## Features

- **Hexagonal Architecture Design:** Utilizes a layered architecture for improved modularity and separation of concerns.
- **Adapters and Ports:** Defines clear boundaries between internal and external services for flexible integrations.
- **Scalability and Maintainability:** Designed to accommodate changes and expansions while maintaining a clear structure.

## Tech Stack

- **Nest.js:** Utilized as the primary backend framework for creating APIs based on a modular design.
- **Database (PostgreSQL):** Integrated for storing task data.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/alexarevalo9/todo-list-back-hexagonal-architecture
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Set up the database and environment variables as required.

4. Start the backend server:

   ```bash
   npm run start:dev
   ```

## Hexagonal Architecture Overview

The backend follows the Hexagonal Architecture, comprising various layers:

- **Domain Layer:** Contains core business logic and entities.
- **Application Layer:** Implements use cases and orchestrates the flow of data.
- **Infrastructure Layer:** Deals with external concerns such as databases, APIs, and other external services.

Please refer to the codebase for detailed insights into the architectural layers and their functionalities.

## License

This project is licensed under the MIT license. See the [LICENSE](https://github.com/alexarevalo9/todo-list-back-hexagonal-architecture/blob/main/LICENSE) file for more details.
