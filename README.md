# 5413-stupid-car-3.0版本，stupid 视觉
a still stupid car but has already modify some params

！！！请注意，愚蠢的Ubuntu无法识别空格，因此在本地尝试编译前，请将stupid car中间的空格改为下划线！！！
about 3.0版本：
sudo apt-get install ros-noetic-find-object-2d，然后在主目录下新建objects文件夹，把模板4.png拷贝进去，正常launch即可，
此版本无导航功能，需要手动把车子开到附近

 更新了新版pgm地图，看了一些杂七杂八的git code 初步调参，还有一些问题。。。
 
 一些可能会遇到的问题：
 
 编译错误，build里面的路径还是我的，请直接删除build和devel文件夹再重新catkin_make
 
 缺东西：sudo apt-get install ros-noetic-teb-local-planner
 
 sudo apt-get install ros-noetic-rviz-imu-plugin

![stupid car](https://github.com/TheBestGroup11/5413-stupid-car/assets/147392750/9c5f721d-8c2a-4c97-a20f-8a8fc7602786)
