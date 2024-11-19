FROM mcr.microsoft.com/devcontainers/cpp:dev-ubuntu24.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update
# Install default packages
RUN apt-get -y install git tree
# Install C/C++ build packages
RUN apt-get -y install cmake ninja-build clang
# Install static analysis packages
RUN apt-get -y install clang-tidy cppcheck
# Install python packages
#RUN apt-get -y install software-properties-common
#RUN add-apt-repository ppa:deadsnakes/ppa -y
RUN apt-get -y install python3.12 python3.12-dev python3.12-venv
RUN apt-get -y install googletest