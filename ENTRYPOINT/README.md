### ENRTYPOINT

ENTRYPOINT instruction is also used to run the container same like CMD but it has few exceptions.

1. We cannot override the it, but CMD can be overriden.
2. If we try to override the ENTRYPOINT during the container run time,  then it will append to the ENTRYPOINT command but gives you the error.
3. CMD will pass the arguments to the ENTRYPOINT, if we don't mention anything during the run time.
4. CMD will provide default arguments to the ENTRYPOINT, it we don't provide anything in the ENTRYPOINT command.
5. We can always override the CMD command during the run time and then will pass that argument to the ENTRYPOINT.
6. It's recommended to use both CMD and ENTRYPOINT our dockerfile for the best results.
7. We can stop misusing our images with other commands with ENTRYPOINT.