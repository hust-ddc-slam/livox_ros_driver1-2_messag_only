# livox_ros_driver1-2_messag_only
Only livox_ros_driver and livox_ros_driver2 message.


## How-to-use

If you installed `livox_ros_driver` but still need "livox_ros_driver2::CustomMsg", or otherwise,  
You just install the other message.


1. Copy the package into your workspace  
2. Build the message  
3. copy `livox_ros_driverx/cmake` folder into `YOUR_Workspace/devel/share/`
4. Change the "CMakeLists.txt" in your codes to find .cmake if necessary