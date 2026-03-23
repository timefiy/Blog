FROM nginx:alpine
RUN rm -f /etc/nginx/conf.d/default.conf
COPY default-docker.conf /etc/nginx/conf.d/default.conf
COPY dist/ /usr/share/nginx/html/
