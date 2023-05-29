# simple dockerfile to test OCP s2i using Dockerfile 

FROM ubuntu:18.04

# Changing parameters of the Dockerfile to generate a new output in OCP pod.
# CMD ["/bin/bash", "-c", "sleep infinity"]
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
