FROM  nginx:1.23.0

COPY sample.conf /etc/nginx/conf.d

RUN echo "now building..."
RUN nginx -t
RUN service nginx restart