INFO
------------
It is an extension for [dtrontestit](https://github.com/arturgummel/dtrontestit) which 
allows to test multiple autonomous platforms navigating in the Stage simulator.<br/>

SETUP
-----------
You can either download it here (https://github.com/arturgummel/robots_stage) or clone the repository.<br/>
`$ cd /catkin_ws/src`<br/>
`$ git clone https://github.com/arturgummel/robots_stage.git`<br/>
`$ cd /catkin_ws && catkin_make`

Executing the Stage simulator
-----------
Navigate to the “catkin_ws” directory and source files:<br/>
`$ cd /catkin_ws`<br/>
`$ source devel/setup.bash`

To start Stage simulator, type next command:<br/>
`$ roslaunch robots_stage multiple_robots.launch`

<b>NB!</b>
If there is necessary in GUI view then remove "-g" argument in the <b>“multiple_robots.launch“</b> file on 49 line. And for RVIZ view uncomment 53 line.
