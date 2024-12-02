FROM lcas.lincoln.ac.uk/lcas/ros:jammy-humble-cuda12.2-opengl

RUN sudo apt-get update && sudo apt-get install -y \
    qtbase5-dev \
    libqt5svg5-dev \
    libzmq3-dev \
    libdw-dev \
    && sudo apt-get clean \
    && sudo rm -rf /var/lib/apt/lists/*
