# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.155.1/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version: bionic, focal
ARG VARIANT="focal"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive

# Set environment variables
ENV LANG=C.UTF-8 LC_ALL=C.UTF-8

# RUN apt update
# RUN apt -y full-upgrade

WORKDIR ../..

RUN apt install -y python3 python3-pip
RUN pip3 install --upgrade pip

#/home/vscode/
#RUN pip3 install -r /workspaces/cours-A61/packages/regression_model/requirements.txt
