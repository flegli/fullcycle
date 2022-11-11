FROM nginx:latest

WORKDIR /home/flegli/fullcycle/docker

RUN apt-get update && \
    apt-get install vim -y

COPY html /usr/share/nginx/html

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "nginx", "-g", "deamon off;" ]