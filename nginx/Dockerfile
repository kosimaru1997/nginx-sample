FROM  nginx:1.23.0

COPY sample.conf /etc/nginx/conf.d

# nigix
RUN nginx -t
RUN service nginx restart