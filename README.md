# Rapidpro for TIBA-RW

# rapidpro-docker-compose

A deployable rapidpro docker-compose setup. Batteries included:
- ssl via letsencrypt
- backing services: elasticsearch, postgres, redis, etc.
- celery tasks

To deploy, Run `docker-compose up`

Note: elasticsearch is currently using ephemeral storage.

Works reasonably well on a single host. Will test on docker swarm cluster next.

To test with ngrok, put the ngrok domain as your RAPIDPRO_HOST environment in .env file
