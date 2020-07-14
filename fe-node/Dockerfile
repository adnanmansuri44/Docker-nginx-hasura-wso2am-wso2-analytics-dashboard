FROM nginx:latest
RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf
COPY src /usr/share/nginx/html
COPY config /etc/nginx
EXPOSE 80