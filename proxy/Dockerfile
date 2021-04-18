FROM nginx:1.15.6
RUN apt-get update
COPY nginx.conf /etc/nginx/conf.d/default.conf

HEALTHCHECK CMD curl --fail http://localhost:80 || exit 0