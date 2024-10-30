FROM wordpress:latest

RUN echo "Install WordPress"

COPY ./fukasawa ./wp-content/themes
COPY ./wp-config.php  /

RUN echo "Copy Theme to wp-content folder"