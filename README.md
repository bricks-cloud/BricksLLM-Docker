# BricksLLM Docker
This repository serves as a quick way to try out/develop [BricksLLM AI gateway](https://github.com/bricks-cloud/BricksLLM) using the `docker compose`. It helps set up dependencies such as
* [Postgresql](https://www.postgresql.org/) - BricksLLM uses Postgresql for storing gateway configurations. 
* [Redis](https://redis.io/) - It is used for caching purposes such as rating limiting and cost controlling API calls to third party LLM models.
### Prerequisites
- [docker-compose](https://www.docker.com/products/docker-desktop/)

### Getting started
First set up your OpenAI credential  
```bash
export OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```
Then run docker-compose
```bash
docker-compose up -d
```
