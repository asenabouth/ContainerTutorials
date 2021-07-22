ARG OS_VERSION=18.04
FROM ubuntu:${OS_VERSION}
RUN apt-get update && apt-get install -y fortune cowsay lolcat
ENV LC_ALL=C
ENV PATH /usr/games:$PATH
ENTRYPOINT fortune | cowsay | lolcat