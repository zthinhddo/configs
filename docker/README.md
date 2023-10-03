# References
https://docs.docker.com/engine/reference/builder/
Best practice: https://docs.docker.com/develop/develop-images/dockerfile_best-practices/

# Process steps:
- Begin with FROM syntax (for images)
- Set WORKDIR (for RUN cmd)
- RUN whatever you like (COPY any file that needed first)


## Note ##
RUN: exec cmd that modifies the container image
CMD: exec after container is created
COPY: Copy file from source to container
ADD: Copy file from source to image
