FROM lcas.lincoln.ac.uk/lcas/ros:jammy-humble-cuda12.2-opengl

RUN sudo apt-get update && sudo apt-get install -y \
    qtbase5-dev \
    libqt5svg5-dev \
    libzmq3-dev \
    libdw-dev \
    ros-humble-behaviortree-cpp \
    && sudo apt-get clean \
    && sudo rm -rf /var/lib/apt/lists/*

# RUN cd /tmp; \
#     git clone --depth 1 -b 4.0.2 https://github.com/BehaviorTree/BehaviorTree.CPP.git; \
#     cd BehaviorTree.CPP; \
#     cmake -S . -B build && \
#     cmake --build build --parallel 8 && \
#     sudo cmake --install build
