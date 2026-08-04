FROM ubuntu:24.04

# updating the package cache
# installing curl with prompt confirmation
RUN apt-get update && apt-get install -y curl ca-certificates

WORKDIR /app

COPY greet .

CMD ("./greet")
