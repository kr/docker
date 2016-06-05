FROM ubuntu
MAINTAINER Keith Rarick <kr@xph.us>
RUN apt-get update && apt-get install -y wget sudo
RUN wget -O- https://toolbelt.heroku.com/install-ubuntu.sh | sh
RUN heroku help # "Installing CLI..."
