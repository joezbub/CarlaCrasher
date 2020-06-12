# CarlaCrasher
CarlaCrasher allows you to simulate and follow a self-driving car in [CARLA](https://www.carla.org). However, the car is programmed to break a large proportion of traffic laws to induce as many collisions as possible. An analysis of the memory after these collisions can yield valuable information about the cause of the collisions, including data like steering wheel movements and acceleration and speed values. CarlaCrasher is a great tool for the cyber investigation and memory analysis of self-driving cars in the CARLA simulator. In the future, I aim to creat Volatility plugins to automate the extraction of this valuable data from memory.

![CarlaCrasherDemo1](images/ccdemo1.png)

# Install
Clone the repository into CARLA's PythonAPI directory, so CarlaCrasher can access the CARLA module `.egg` file.

# Run
In the CarlaCrasher directory, run `python crasher.py`. You should see a pygame window pop up with a self-driving car driving through the simulator.
