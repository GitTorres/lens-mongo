# Mongodb service with Mongo Express to view collections in a browser.

## images used:
`mongo`, `mongo-express:0.54`

## commands

+ `make up` to run the container

+ `make down` to stop the container and prune orphans

+ `make bash` to interact with the container

## steps
+ add `.env` file to top-level directory, and provide the root user credentials
    + if this is not done before `make up` is run
        + run `make down`
        + run 'rm -rf ./data/mongo`
        + run `make up`
+ run `make up` in terminal