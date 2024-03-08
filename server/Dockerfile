FROM ubuntu

RUN apt update && apt -y install g++ cmake nano git

RUN git clone https://github.com/chandrabhan-vns/docker_examples.git app

RUN cd /app/server && cmake . && make
