FROM ubuntu:18.04
WORKDIR /skriptat
COPY script.sh .
RUN chmod +x script.sh
RUN apt-get update && apt-get install -y curl
CMD ["/skriptat/script.sh"]

