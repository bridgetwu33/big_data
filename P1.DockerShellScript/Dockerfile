FROM ubuntu:22.04

RUN apt-get update && apt-get install -y wget unzip

COPY count.sh /bin/count.sh

RUN chmod +x /bin/count.sh

CMD ["bash", "/bin/count.sh"]