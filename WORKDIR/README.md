## WORKDIR

WORKDIR is used to set the path to the image/container.

Example:

FROM almalinux
RUN cd /tmp/
RUN touch hi.txt

In the above example, the docker image and container will run the first RUN command and it goes to that /tmp/ folder and the next RUN command will not create the touch file inside the /tmp/ folder because once it executes the first RUN command then by default it will go the root directory and create the touch file in the root directory.

This is where we can use WORKDIR is useful to set our path. 

