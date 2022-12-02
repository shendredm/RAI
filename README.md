[Things written in square brackets are instructions for you. dont copy them in terminal]
[Open a terminal on desktop and start copying following commands]
[If any error shows up, dont go to next step. Try to correct the error by rerunning the current command]]


[ROS Noetic:]

sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
[It Will ask for password. type password and press enter]

sudo apt install curl
[Press Y and then Enter when asked]

sudo apt install curl # if you haven't already installed curl
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
[Press Enter]

sudo apt update

sudo apt upgrade
[when asked, press Y and then enter]

sudo apt install ros-noetic-desktop-full
[when asked, press Y and then enter]

echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
source ~/.bashrc


[Pybullet:]

sudo apt install python3-pip
[Type password and press enter}
[Press Y and then Enter when asked]

pip install pybullet


[Open AI Gym:]

pip install gym

pip install pygame


[Pytorch:]

pip3 install torch==1.10.2+cpu torchvision==0.11.3+cpu torchaudio==0.10.2+cpu -f https://download.pytorch.org/whl/cpu/torch_stable.html


[TensorFlow:]

pip install tensorflow

[The End]
