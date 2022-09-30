FROM nginx:1.21-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
COPY ./cert/certificado.pem /etc/ssl/certs/
COPY ./cert/privada.pem /etc/ssl/certs/
