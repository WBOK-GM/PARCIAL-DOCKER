FROM alpine:3.20

RUN apk add --no-cache curl

WORKDIR /app 

COPY mensaje.txt /app

CMD ["cat","mensaje.txt"]
