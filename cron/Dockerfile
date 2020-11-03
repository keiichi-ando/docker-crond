FROM alpine:3.9.6

RUN apk --update add tzdata \
    && cp /usr/share/zoneinfo/Asia/Tokyo /etc/localtime \
    && rm -rf /var/cache/apk/*

CMD crond -l 1 -f