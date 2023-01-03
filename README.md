# Docker Image of a repository

- create dockerfile

          # specify the node base image with your desired version node:<version>
          FROM node:16
          # replace this with your application's default port
          EXPOSE 8888

# startting repository

- write to console

          docker run -it --rm --name my-running-app meetup-getup-docker
