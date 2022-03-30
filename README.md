This project will be used for learning ROS2, implementing deep learning,
playing around with pount clouds and testing

path for project is: /home/martin/projects/uni

Installed things:
ROS2 (https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html):
sudo apt update && sudo apt install curl gnupg2 lsb-release
sudo curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.key -o /usr/share/keyrings/ros-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/ros-archive-keyring.gpg] http://packages.ros.org/ros2/ubuntu $(source /etc/os-release && echo $UBUNTU_CODENAME) main" | sudo tee /etc/apt/sources.list.d/ros2.list > /dev/null
sudo apt update
sudo apt install ros-foxy-desktop

Source ROS2:
source /opt/ros/foxy/setup.bash
