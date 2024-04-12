
# Carla Object Detection

Carla is an open world simulator which is widely used for training self driving cars and this project integrates YOLOv4 into Carla simulator which detect objects in real time while driving the car, which can be later used for training the model.



## Deployment

Firstly run the carla server in command windows

```bash
CarlaUE4 -windowed -carla-server
```

Then to run the object detection with a simulated car run the manual control file in the folder

```bash
Python manual_control.py
```

