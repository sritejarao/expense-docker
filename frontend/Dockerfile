FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /usr/share/nginx/nginx.conf
COPY nginx.conf /usr/share/nginx/nginx.conf
COPY code /usr/share/nginx/html/
