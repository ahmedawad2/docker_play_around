#created by ahmed awad

FROM debian:buster-slim

RUN apt-get update && apt-get install -y nginx

RUN rm /etc/nginx/nginx.conf

COPY nginx.conf /etc/nginx

EXPOSE 80

#CMD nginx -g 'daemon off;'

CMD ["nginx", "-g", "daemon off;"]