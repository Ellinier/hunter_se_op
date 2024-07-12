## Basic usage of hunter_se related ROS packages

1. Install dependent packages

    
    
2. Clone the packages into your catkin workspace and compile

    (the following instructions assume your catkin workspace is at: ~/catkin_ws/src)

    ```
    $ cd ~/catkin_sensor/src
    $ git clone https://github.com/Ellinier/hunter_se_op.git
    $ cd ..
    $ catkin build hunter_se_op
    ```

3. Start related drivers

    ```
    cd ~/catkin_sensor/src
    bash setup_hunter.sh
    ```
TODO: check the internet link to velodyne

4. Start camera, lidar, hunter_se

    ```
    launch hunter_se_op hunter_se_op.launch
    ```
