# What is it
A docker file for ROS Noetic  (ROS 1)

# One time setup
````
docker build -f ./ubuntu_20_04_ros_dockerfile_1 .
# do "docker images" and find the hash of the image just created; "04f7aeebc6f7" below
docker tag 04f7aeebc6f7 ros1_harish
# tag it so it's easier to start, etc.

# @todo simplify
````

# Everytime setup and cleanup
````
docker run -it ros1_harish /bin/bash
````

Do this when done:
````
On the command prompt
#exit
````

# To fix
root@7d0ca2f060c8:/# roscore
bash: roscore: command not found