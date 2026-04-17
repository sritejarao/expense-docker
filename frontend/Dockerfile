FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /usr/share/nginx/nginx.conf
COPY nginx.conf /usr/share/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY default.conf /etc/nginx/conf.d/default.conf
COPY code /usr/share/nginx/html/
