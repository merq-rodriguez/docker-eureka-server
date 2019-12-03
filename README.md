# Eureka Server

Implementation of eureka server with docker


# 1. build the Eureka server using maven
`mvn clean install`

# Ór
`mvn clean install -DskipTests`

# 2. build the docker image
`docker build --no-cache=true -t repo/eureka-server .`

# 3. run the container
`docker run -d repo/eureka-server`

# Ó
# build the docker container using docker-compose
`docker-compose up -d`

