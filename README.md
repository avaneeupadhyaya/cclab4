 ### Docker Advanced Chat Lab

- A simple chat application built using Docker Compose and RabbitMQ.
- Two users communicate through message queues, and Docker volumes are used to store chat history persistently.

### Run
```
docker compose up rabbitmq
docker compose run --rm user-a
docker compose run --rm user-b
```

### Persistence

- After sending messages, stop and restart the system to see previous chat history saved via volumes.
