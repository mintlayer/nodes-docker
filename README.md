# Mintlayer local node cluster

How to run:

1. `docker-compose up`
2. Add Aura and Grandpa keys over RPC
3. Kill all containers
4. `docker-compose up`

If you make changes to `Dockerfile`, remember to run as `docker-compose up --build`

If you want to destroy previous chain and use a new chain, run `docker-compose up --force-recreate`
