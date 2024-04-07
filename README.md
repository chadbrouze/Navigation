
Protect Environment:
The project environment is in a unity game. The objective is to collect as many yellow bannanas (+1 point) and avoid as many purple bananas (-1 point) as possible. The observation/state space has 37 values including velocity and a ray based world perception. The 4 actions forward back left and right. The state space is considered solved when the algorithm gets an average of 13 points over 100 episodes; however, my algorithm does achieve better performance than that.



Getting Started:

Dependencies
tensorflow==1.7.1
Pillow>=4.2.1
matplotlib
numpy>=1.11.0
jupyter
pytest>=3.2.2
docopt
pyyaml
protobuf==3.5.2
grpcio==1.11.0
torch==0.4.0
pandas
scipy
ipykernel

Downloading unity environment:
Github: https://github.com/Unity-Technologies/ml-agents
Mac: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip
Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip


Instructions:
Run all of the code cells in Navigation.ipynb. This is dependant on the model and agent scripts so ensure they are in the same directory.

