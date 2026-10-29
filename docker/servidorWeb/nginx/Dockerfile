FROM debian:latest
MAINTAINER Ivan Rubert <ivanrubert23@gmail.com>

# Actualizamos e instalamos Nginx
RUN apt update && apt upgrade -y && apt install -y nginx && \
    rm -rf /var/lib/apt/lists/*

# Exponemos el puerto 80
EXPOSE 80

# Comando para iniciar Nginx en primer plano
CMD ["nginx", "-g", "daemon off;"]
