### CMD

CMD is the instruction that runs the container. In order to keep container in running state, then CMD needs run infinite times.

If we have multiple CMD instructions in our Dockerfile, then the last CMD instruction will run.

### RUN VS CMD

RUN ----> It will execute at the time of image creation

CMD ----> It will execute at the time of container running.