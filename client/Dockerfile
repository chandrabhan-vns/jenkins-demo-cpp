FROM ubuntu

RUN apt update && apt -y install g++ cmake nano git
# Need to check
RUN git clone https://github.com/chandrabhan-vns/docker_examples.git app

# WORKDIR /app/client

RUN cd /app/client && cmake . && make
