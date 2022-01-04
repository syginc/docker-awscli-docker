FROM ghcr.io/syginc/docker-awscli:python3.7

ENV DOCKER_VERSION "18.09.0"

RUN curl -L -o /tmp/docker.tgz https://download.docker.com/linux/static/stable/x86_64/docker-$DOCKER_VERSION.tgz && \
    tar -xz -C /tmp -f /tmp/docker.tgz && \
    mv /tmp/docker/* /usr/local/bin && \
    rm -rf /tmp/docker*
