# Distribut.io





# Architecture 

## BOINC 

![Test](https://upload.wikimedia.org/wikipedia/commons/9/94/Boincarchitecture.png)

## OpenStack

![image](https://user-images.githubusercontent.com/13450068/214101879-ade66e79-8db5-4855-8a87-5d468a55b473.png)


# Installation 


## BOINC 


## OpenStack

## Requirements

If you are hosting your server on a Linux machine, the requirements are,

* [Docker](https://docs.docker.com/engine/installation/) (>=17.03.0ce)
* [docker-compose](https://docs.docker.com/compose/install/) (>=1.13.0 but !=1.19.0 due to a [bug](https://github.com/docker/docker-py/issues/1841))
* git

(Note that Docker requires a 64-bit machine and Linux kernel newer than version 3.10)

If your are hosting your server on Windows/Mac, you should use either,

* [Docker for Mac](https://docs.docker.com/docker-for-mac/install/#download-docker-for-) (>=17.06.0ce)
* [Docker for Windows](https://docs.docker.com/docker-for-windows/install/) (>=17.06.0ce)

If you Windows/Mac system is too old to run either of those, you can use instead, 

* [Docker Toolbox](https://docs.docker.com/toolbox/overview) (>=17.05.0ce)

There are no other dependencies, as everything else is packaged inside of Docker. 

The server itself runs Linux. On Windows/Mac, Docker does the job of transparently virtualizing a Linux machine for you. The commands given in this guide should be run from your system's native terminal, unless you are running Docker Toolbox, in which case they should be run from the "Docker Quickstart Terminal" (and on Windows you will need to add `.exe` to the end, e.g. `docker.exe` instead of `docker`).
