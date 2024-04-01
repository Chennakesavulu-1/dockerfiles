FROM nginx
# removing default html
RUN rm -rf /usr/share/nginx/html/index.html
# file should be available in current directory were dockerfile exist.
COPY index.html /usr/share/nginx/html/index.html