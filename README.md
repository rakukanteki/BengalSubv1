## Repository Structure:
This is an offical and structured repository of the BengalSub containing the entire codebase for the RoboSub'25 competition.
```
BengalSubv1
├── auv
│   ├── device
│   │   ├── # everything related to the sensors
│   │   ├── # each device should have its own file/folder
│   ├── localization 
│   │   ├── # TODO
│   ├── mission 
│   │   ├── # Mission classes
│   │   ├── # see auv/mission/template_mission.py for an example
│   ├── motion
│   │   ├── # Actuators code
│   │   ├── # each actuator should have its own file/folder
│   ├── cv
│   │   ├── # All CV classes and functions
│   ├── utils
│   │   ├── # utility functions
├── scripts
│   ├── # bash scripts
├── mission
│   ├── # Mission files (calling mission classes)
├── tests
│   ├── # Unit tests (pytest)
├── config.json # where all the config values used in mission files are stored
├── setup.py # setup file for pip install
├── .gitignore
├── README.md
```

## Initialization:
