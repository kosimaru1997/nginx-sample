FROM  nginx:1.23.0

COPY sample.conf /etc/nginx/conf.d

# nigix
RUN nginx -t
RUN service nginx restart
# vimを入れる
RUN apt-get update
RUN apt-get install -y vim