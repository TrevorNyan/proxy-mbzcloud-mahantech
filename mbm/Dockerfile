FROM alpine:latest
WORKDIR /
COPY . .
RUN apk add --no-cache libc6-compat 
CMD ["/bmanager"]
EXPOSE 8000