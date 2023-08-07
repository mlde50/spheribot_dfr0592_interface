# spheribot_dfr592_msg

create a new repository on the command line

echo "# spheribot_dfr592_msg" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mlde50/spheribot_dfr0592_interface.git
git push -u origin main


Build 
```
colcon build --packages-select spheribot_dfr0592_interface
```

```
. install/setup.bash
```

```
ros2 interface show  spheribot_dfr0592_interface/msg/Command
ros2 interface show  spheribot_dfr0592_interface/msg/Velocity
ros2 interface show  spheribot_dfr0592_interface/msg/Encoder