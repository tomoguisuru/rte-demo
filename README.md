# Real-Time Events Demo App
Basic implementation for RT Events

### Requirements
- [Docker](https://www.docker.com/get-started/)
- Edg.io Account
  - [User ID/Owner ID](https://cms.uplynk.com/static/cms2/index.html#/settings)
  - [API Key](https://cms.uplynk.com/static/cms2/index.html#/settings/integration-keys)
- [Real Time Events Access](https://cms.uplynk.com/static/cms2/index.html#/live-events/real-time-events)


## Getting Started

#### Step 1:
Clone the project
```bash
git clone --recurse-submodules git@github.com:tomoguisuru/rte-demo.git
```

#### Step 2:
Copy the example `.env.example` file to `.env`
```bash
cp .env.example .env
```

#### Step 3:
Edit the newly created `.env` file and update the `UPLYNK_OWNER` and `UPLYNK_APIKEY` with your user/owner id and API Key

#### Step 4:
Build the project
```bash
docker-compose build
```

#### Step 5:
Start the project
```bash
docker-compose up
```

#### Step 6:
Open the [demo](http://localhost:4200/home) in your browser

#### Step 7:
Stop the project
```bash
docker-compose down
```

### Under the Hood
- **Frontend**: [Ember](https://emberjs.com/)
- **API**: [Express](https://expressjs.com/)
- **DB**: [PostgresSQL](https://www.postgresql.org/)
- **Caching**: [Redis](https://redis.com/)

### References
- Edg.io Streaming Help Center
  - [Real-Time Events API Docs](https://docs.edgecast.com/video/index.html#Develop/Real-Time-Events-API.htm)