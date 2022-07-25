FROM inseefrlab/onyxia-vscode-python:latest
# open bash shell to interact with the container (shabang)
SHELL ["/bin/bash", "-c"]

USER root
# old Lab 0 installation of R and cython instructions
RUN apt-get update && \
    apt-get install -y r-base openjdk-11-jre-headless && \
    #installer Cython
    pip install Cython 

USER ${USERNAME}
