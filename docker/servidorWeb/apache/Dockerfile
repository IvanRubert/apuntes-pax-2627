FROM debian:latest
MAINTAINER Ivan Rubert <ivanrubert23@gmail.com>

# Actualizamos e instalamos Apache2
RUN apt update && apt upgrade -y && apt install -y apache2 && \
    rm -rf /var/lib/apt/lists/*

# Exponemos el puerto 80
EXPOSE 80

# Comando para iniciar Apache2 en primer plano
CMD ["apache2ctl", "-D", "FOREGROUND"]
