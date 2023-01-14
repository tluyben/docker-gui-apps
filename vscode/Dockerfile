# Dockerfile
FROM debian:11-slim
COPY install .
RUN chmod 755 ./install
COPY runvscode .
RUN chmod 755 ./runvscode
CMD ["./install"]
