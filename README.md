# Lift_Efficiency_improvement_using_CV
This project uses real-time object detection to optimize elevator usage in buildings. CCTV footage analyzes waiting crowds to decide if the elevator should stop, reducing wait times and improving efficiency.

## FLOW OF THE MODEL

![flow drawio](https://github.com/Saptharishee/Lift_Efficiency_improvement_using_CV/assets/82307484/133bdb1c-650c-4a94-a4ae-99fa6240e81c)
Fig. 1. Figure 1: Flow diagram of the model
The proposed flow of the model for the Lift Efficiency
Development project is as follows:
1) CCTV cameras capture images of passengers on the
floor.
2) The images are sent to the control center.
3) The control center defines the region of interest (ROI)
in the images, which is a sub-region that contains the
relevant information for elevator management.
4) The control center uses YOLOv8, a real-time object
detection algorithm, to detect the number and location
of passengers in the images.
5) Based on whether there is a passenger or not in the
defined region, the control center decides whether to stop
the lift or not.
6) The control center communicates these decisions to
the lift carrier, which is the module that controls the
movement and operation of the elevator.
7) The lift carrier executes the commands from the control
center and provides the status of the elevator.

