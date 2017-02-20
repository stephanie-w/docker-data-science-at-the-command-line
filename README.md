A docker container for the "Data Science at the Command Line" book

This repository contains everything to build a doker container to use with the book [Data Science at the Command Line](http://datascienceatthecommandline.com).


To build the container :

    cd docker-data-science-at-the-command-line
    docker build -t docker-data-science-at-the-command-line .

To run the container :

    docker run -v `pwd`:/data -it docker-data-science-at-the-command-line /bin/bash
