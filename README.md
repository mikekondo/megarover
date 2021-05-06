# megarover

# 実行環境

WPT_Robotはプログラミング言語 C++で記述されています。

| Linux Ubuntu 16.04 LTS |                   gcc 5.4.0                    |

| Linux Ubuntu 18.04 LTS |                   gcc 5.4.0                    |

シミュレーション環境　Gazebo9

32 ビット OS での動作確認はしていないので、必要な場合はご自分で試してください。



# 実行方法

```
roslaunch megarover_samples vmegarover_with_sample_world.launch
```

![megarover](https://user-images.githubusercontent.com/65348333/117230798-c9260800-ae58-11eb-8388-f78920fba7c7.png)

![megarover2](https://user-images.githubusercontent.com/65348333/117230794-c6c3ae00-ae58-11eb-8431-25347d852faf.png)

# 使用するためのROSpackage

・sudo apt install ros-melodic-gmapping

・sudo apt install ros-melodic-map-server

・sudo apt install ros-melodic-amcl

・sudo apt install ros-melodic-move-base

・sudo apt install ros-melodic-gazebo-ros

・sudo apt install ros-melodic-gazebo-ros-control 

・sudo apt install ros-melodic-ros-control

・sudo apt install ros-melodic-ros-controllers

・sudo apt-get install ros-melodic-move-base-msgs

・sudo apt-get install ros-melodic-navigation
