# AmebaPro_OpenDuck_Mini

## OpenDuck Mini v2
### source: [Open_Duck_Mini](https://github.com/apirrone/Open_Duck_Mini)

### PCBs
| PCB                      |    Picture    |
|--------------------------|---------------|
| Front open-case view     | <img width="25%" src="https://github.com/rkuo2000/AmebaPro_OpenDuck_Mini/blob/main/pics/OpenDuck_mini_v2_front_open.png?raw=true"> |
| I2C-GPIO extension board | <img width="25%" src="https://github.com/rkuo2000/AmebaPro_OpenDuck_Mini/blob/main/pics/OpenDuck_mini_v2_I2C_GPIO_adapter.png?raw=true"> |
| Main board (RPi4B)       | <img width="25%" src="https://github.com/rkuo2000/AmebaPro_OpenDuck_Mini/blob/main/pics/OpenDuck_mini_v2_RPi4B.png?raw=true"> |)
| Serial Bus Servo Adapter | <img width="25%" src="https://github.com/rkuo2000/AmebaPro_OpenDuck_Mini/blob/main/pics/OpenDuck_mini_v2_serial_bus_servo_adapter.png?raw=true"> |

---
### Servo: STS3215

#### [Arduino STS_Servos driver](https://github.com/DeltaEngine/FeetechStsServos)
* [STSServoDriver.h](https://github.com/DeltaEngine/FeetechStsServos/blob/main/src/STSServoDriver.h)
* [STSServoDriver.cpp](https://github.com/DeltaEngine/FeetechStsServos/blob/main/src/STSServoDriver.cpp)

#### example:
* [ChangeServoId.ino](https://github.com/DeltaEngine/FeetechStsServos/blob/main/examples/ChangeServoId/ChangeServoId.ino)
* [SimpleMotion.ino](https://github.com/DeltaEngine/FeetechStsServos/blob/main/examples/SimpleMotion/SimpleMotion.ino)

### Motor IDs
```
{
    "left_hip_yaw": 20,
    "left_hip_roll": 21,
    "left_hip_pitch": 22,
    "left_knee": 23,
    "left_ankle": 24,
    "neck_pitch": 30,
    "head_pitch": 31,
    "head_yaw": 32,
    "head_roll": 33,
    "right_hip_yaw": 10,
    "right_hip_roll": 11,
    "right_hip_pitch": 12,
    "right_knee": 13,
    "right_ankle": 14,
}
```

---
## AmebaPro2
### [Hub8735-Ultra](https://github.com/ideashatch/HUB-8735)
<img width="10%" src="https://github.com/rkuo2000/AmebaPro_OpenDuck_Mini/blob/main/pics/Hub8735_Ultra.png?raw=true">
