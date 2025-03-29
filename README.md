# gazebo_world

## Description

### bookstore_world、hospital_world、racetrack_world、small_house_world
#### source

```shell
https://github.com/aws-robotics
```



### mecanum_gazebo
#### source

```shell
https://github.com/diddytpq/Mecanum-robot-slam-gazebo-study.git
```

#### Use

**mecanum_gazebo.launch** 

`world_name`:

- district：It represents the neighborhood environment, which includes dynamic pedestrians
- open_enclosed_area：It represents an open and closed environment that contains dynamic pedestrians. Concise and suitable for adding multiple dynamic pedestrians for deep reinforcement learning

#### Supplement

​	Add dynamic pedestrians to the world file.

​	There are two behavioral patterns: fixed trajectory and random trajectory

​	Please refer to the world file corresponding to the `district` in detail

```xml
```

