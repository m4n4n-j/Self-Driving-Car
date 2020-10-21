# Self Driving Car AI using Kivy and PyTorch/Keras

We designed a car using Kivy framework used 3 sensors in the car to perceive the enviornment.
Then We trained the car using Reinforcement Learning(Deep Q Network)

## Requirements

* [Kivy](https://kivy.org/#home)
Kivy is an Open source Python library for rapid development of applications that make use of innovative user interfaces, such as multi-touch apps.

* [PyTorch](https://pytorch.org/)
PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing, primarily developed by Facebook's AI Research lab.

* Some Python libraries such as Numpy and Matplotlib.

# To Run Self Driving Car:
- Run below command, to start an emulated environment where you can see a toy car (Do ensure that the enviornment is set up)
- Use your mouse, left click and drag, to drop sands
- With mouse now you can create your own road/sand ways, where the car will learn to drive on its own.
- Go ahead and create different paths and see how it adopts to the environment 
- We implemented this project using both PyTorch and Keras to implement Deep Learning based Q Learning, a special Reinforcement Learning algorirthm that learns the environment and helps the agent(car) to navigate avoiding the sand.

```
python map.py
```

## Description

We need an environment to emulate our car and sensors with our own rules. Kivy is a Python UI development framework, which can be used for this purpose, as it allows user interaction programming very easy, like mouse / touch interactions.
We used Kivy to make the car environment .

Then We used Experience Replay and Deep Q intuition to create an AI which uses 3 sensors(front, left & right) in the car to detect 'sand(yellow)' We.e. out of it's road areas . If it runs on the sand it gets punishment/penalized and it tries not to repeat that again.

We used a deep neural network comprising of two hidden layers. First layer having 30 nodes and Second layer having 20 nodes.

## Reference

* https://medium.com/@mageswaran1989/self-driving-car-with-deep-learning-8eb2c418acb6
