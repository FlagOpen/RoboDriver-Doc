# 使用 RoboXStudio 平台

拉取这个库，里面是安装程序：https://github.com/FlagOpen/DataCollect_WebUI.git

在安装完WebUI后，运行这个启动。

```
python3 robodriver/scripts/run.py \
  --robot.type=so101_follower_dora \
  --teleop.type=so101_leader_dora 
```

:::tip[启动顺序注意]
需要先将机器自带的程序先启动，比如ROS、Dora，确保编写的`robodriver_robot_`和`robodriver_teleoperator_`能接收到数据
:::