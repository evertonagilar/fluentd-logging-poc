FROM ubuntu:latest

COPY . .

RUN chmod +x logify.sh && \
    mkdir -p /var/log/logify && \
    ln -sf /dev/stdout /var/log/logify/app.log

CMD ["./logify.sh"]
