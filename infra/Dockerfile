FROM julia:1.8.5

RUN apt-get update -y && \
    apt-get install -y git

COPY packages.jl /tmp/packages.jl
RUN julia /tmp/packages.jl && \
    rm /tmp/packages.jl
