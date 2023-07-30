### ARG

ARG is used to pass the variables during the image creation.

1. It is the only insturction used before FROM instruction but ARG declared before FROM cannot accessed after FROM instruction.

### Using ARG and ENV for the best results

Create ENV variable and assign the ARG variable to ENV variable, then we can access that ARG variable in the container with the help of ENV.
