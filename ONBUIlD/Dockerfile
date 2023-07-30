FROM almalinux
RUN yum install nginx -y
# When the image owner runs the below command, it will not run but it will run when others use this image.
ONBUILD ADD simple.txt /tmp