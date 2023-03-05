FROM debian:latest

RUN apt-get update && apt-get install -y libnginx-mod-http-lua libnginx-mod-http-ndk

CMD ["nginx", "-g", "daemon off;"]
