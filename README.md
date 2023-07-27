# Project: Where Am I?

<img src=https://github.com/tstaisyu/Where_Am_I/Screenshot_of_localized_robot.png width=500 />

# To start a simulation

```sh
$ cd (YourHomeFolder)/catkin_ws
$ git clone --recursive https://github.com/tstaisyu/Where_Am_I.git src
$ catkin_make
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```

# To start AMCL (on another Terminal)

```sh
$ source devel/setup.bash
$ roslaunch localization amcl.launch
```
# To start teleop (on another Terminal)

```sh
$ source devel/setup.bash
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```