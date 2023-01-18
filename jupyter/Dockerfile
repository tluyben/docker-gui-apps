# Dockerfile
FROM debian:11-slim
COPY install .
RUN chmod 755 ./install
COPY runjupyter .
RUN chmod 755 ./runjupyter
CMD ["./install"]
