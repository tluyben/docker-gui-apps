# Dockerfile
#FROM debian:11-slim
FROM ubuntu:latest
COPY install .
RUN chmod 755 ./install
COPY runjupyter .
RUN chmod 755 ./runjupyter
COPY chromium .
RUN chmod 755 ./chromium
CMD ["./install"]
