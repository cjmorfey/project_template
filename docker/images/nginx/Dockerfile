FROM nginx:1.7
COPY content /opt/kuber-volume/html
COPY conf /var/www/kuber-volume/html
VOLUME /var/www/kuber-volume/html
VOLUME /opt/kuber-volume/html
EXPOSE 80
ENV NGINX_HOST=test.kub