# base image ubuntu
FROM ubuntu:20.04

# running commands to install python
RUN apt-get update && apt-get install -y python3

# copying your application into the container
COPY hello.py .

# default command - run my container
ENTRYPOINT ["python3", "hello.py"]