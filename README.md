# Currency Exchange Rate Tracker

## Project Purpose
The Currency Exchange Rate Tracker is a backend service that monitors currency exchange rates and alerts users when specific currency pairs reach user-defined thresholds. It leverages a microservices architecture with technologies like RabbitMQ for event-driven communication, Redis for caching frequently accessed data, and MongoDB for persistent storage.

## Tech Stack
- **Backend**: C#
- **Data Storage**: MongoDB
- **Caching**: Redis
- **Event Handling**: RabbitMQ
- **Containerization**: Docker
- **Deployment**: Azure

## Project Structure
- **/api**: REST API service for managing users and their subscription preferences.
- **/rate-fetcher**: Microservice that fetches currency rates from an external API and updates the cache.
- **/notifications**: Service to handle notifications based on user-defined thresholds.
- **/configs**: Configuration files for RabbitMQ, Redis, MongoDB, etc.
- **/Docker**: Dockerfiles and docker-compose setup for container orchestration.
