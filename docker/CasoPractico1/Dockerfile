FROM ubuntu:latest
RUN apt update && apt install -y nano && apt purge --auto-remove && apt clean && rm -rf /var/lib/apt/lists/*

CMD /bin/bash