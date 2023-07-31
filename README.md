# usb_cam

## Available launch files

This package provides launch files for the logitech webcam, endoscope, d435 colour camera, and one of the d435 IR cameras.

```
roslaunch usb_cam logitech_webcam.launch
```

```
roslaunch usb_cam endoscope_cam.launch
```

```
roslaunch usb_cam d435_colour_cam.launch
```

```
roslaunch usb_cam d435_ir_cam.launch
```

## Reconfigurable Parameters

This package uses the [dynamic_reconfigure](http://wiki.ros.org/dynamic_reconfigure) ROS package reconfigure the camera parameters during operation. To reconfigure the parameters, simply start a camera node and then run `rosrun rqt_reconfigure rqt_reconfigure`. Then click the name of the node and move the sliders to change the parameter values.

## Original readme

To view the original readme for this package, see [orig_README.md](orig_README.md).
