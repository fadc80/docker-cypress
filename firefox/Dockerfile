FROM cypress/base:latest

RUN echo "deb http://deb.debian.org/debian/ unstable main contrib non-free" >> /etc/apt/sources.list.d/firefox.list
RUN apt update && apt -y install -t unstable firefox