FROM alpine
WORKDIR /usr/src/app

COPY files/docs /usr/src/app/code/docs
COPY files/notes.txt /usr/src/app/code/
COPY files/extra ./extra

WORKDIR /usr/src/app/code

CMD ["ls" , "-R", "/usr/src/app"]