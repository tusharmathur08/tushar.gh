# syntax=docker/dockerfile:1

FROM ubuntu:latest

RUN apt update && apt install git -y

RUN git clone https://github.com/tusharmathur08/tushar.gh.git

RUN pwd && ls

RUN mkdir -p buildfiles/

RUN cp /tushar.gh/shell/test.sh buildfiles/test.sh

RUN sh buildfiles/test.sh

RUN git clone https://github.com/tusharmathur08/helloworld.git

RUN ls

