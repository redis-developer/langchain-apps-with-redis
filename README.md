# LangChain Applications with Redis

This repository contains examples of how to implement vector search, semantic caching, and LLM session management with Redis.

## Getting started

Before running any of the code available in the Jupyter notebooks, you will need a Redis database. For the sake of convenience, this repository provides a Docker Compose file that spin ups a Redis database for you. Just execute the following command to start it up:

```bash
docker compose up
```

Now you can start following the instructions from the Jupyter notebooks. Have fun!

## Pydantic incompatibilities

If you are using Python 3.14, there are known incompatibilities with Pydantic V1 that can cause an unable to infer type error with RedisVL.

Fix: downgrade to Python 3.13

## License

This project is licensed under the MIT License.
