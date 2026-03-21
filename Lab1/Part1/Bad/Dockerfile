FROM debian
RUN apt-get update 
RUN apt-get install -y cowsay fortune
ENV PASSWORD=1234567890
ENTRYPOINT ["/usr/games/cowsay"]