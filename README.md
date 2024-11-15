# Car Rental Project

## Project Structure
- `services/` - Contains all microservices
  - `kafka-websocket-connector/` - Kafka WebSocket connector service
- `volumes/` - Persistent data storage for services
- `.env` - Environment configuration
- `docker-compose.yml` - Docker services configuration

## Setup
1. Copy `.env.example` to `.env` and configure variables
2. Run `docker-compose up -d`

## Services
- Kafka Broker: Port 9092
- Zookeeper: Port 2181
- Redis: Port 6379
- Redis Commander: Port 8081
- Kafka WebSocket Connector: (specify port) 