# jackal_cartographer
Configuration files for using Velodyne VLP-16 for map generation with google cartographer

You have to use my_robot.launch with roslaunch instead of demo_my_robot.launch
Also, tf map needs to be sorted out and to do that, VLP16 launch file on the robot has to have static_transform_publisher node argument for velodyne.
