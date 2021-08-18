FROM nginx:alpine

LABEL maintainer="Victor Sudakov <vas@4vrs.com>"

COPY nginx.conf /etc/nginx/nginx.conf
COPY html /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d/default.conf
