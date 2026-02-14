# gemini_vla_Doosan-robotic-arm

실행 명령어
colcon build --packages-select gemini_vla  
source install/setup.bash 

ros2 launch dsr_bringup2 dsr_bringup2_rviz.launch.py mode:=real host:=110.120.1.38 port:=12345 model:=e0509



source install/setup.bash 
ros2 launch gemini_vla gemini_vla.launch.py
