FROM ubuntu
MAINTAINER Keith Rarick <kr@xph.us>
RUN apt-get update && apt-get install -y wget sudo
RUN wget -O- https://toolbelt.heroku.com/install-ubuntu.sh | sh
RUN useradd -ms /bin/bash herokucli
USER herokucli
WORKDIR /home/herokucli
RUN heroku version # "Installing CLI..."
RUN rm /home/herokucli/.heroku/autoupdate.last
