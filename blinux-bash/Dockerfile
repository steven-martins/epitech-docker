FROM epitechcontent/blinux:beta
MAINTAINER Thomas Dufour <thomas.dufour@epitech.eu>

RUN zypper -n install \
    emacs             \
    nano              \
    vim

RUN useradd -md /home/bill bill
USER bill
WORKDIR /home/bill/workspace
ENTRYPOINT exec /bin/bash
