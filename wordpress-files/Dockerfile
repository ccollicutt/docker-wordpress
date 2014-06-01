FROM busybox 
MAINTAINER curtis <curtis@serverascode.com>

ADD http://wordpress.org/latest.zip /wordpress.zip
RUN mkdir -p /var/www/html && \
    cd /var/www/html && \
    unzip /wordpress.zip && \
    rm -f /wordpress.zip

CMD ["true"]
