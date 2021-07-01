FROM ubuntu
WORKDIR /tmp/
RUN echo "HI FRIENDS"> /tmp/testfile
RUN apt update -y
RUN apt install git -y
RUN apt install tree -y
COPY rajfile /root/
ADD demo.tar.gz /root/
