# my_stdr_control
my_stdr_control is a package that will move the robot from the Simple 2-Dimensional Robot Simulator (STDR) from its initial position in the bottom left corner to the top left corner.

## Example usage
Keep in mind that this code is derived from and utilizes code from Wyatt Newman's learning_ros repository which can be found here: https://github.com/wsnewman/learning_ros.

With ROS installed, you can run roscore using the command "roscore".
Then, launch the STDR with the following command:
	roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch

After STDR is running, run this package using the following command:
	rosrun my_stdr_control my_stdr_open_loop_commander
	
## Running tests/demos
A video and writeup with my findings are accompanied with this project.
