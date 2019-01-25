# CarND-Kidnapped-Vehicle-Project



[//]: # (Image References)

[image1]: ./Success_images/Running.png "Running of the project"
[image2]: ./Success_images/Success.png "Success message by the simulator"

### Project Description:

The project premise is that a kidnapped vehicle has been put in a unknown environment with no idea of its location. The whole environment is simulated in the Udacity's self driving car simulator. The aim of the project is to predict the vehicle location using a Particle Filter program written in C++. An error is calculated between ground truth values and the predicted locations by the filter. The error has to be within a minimal criteria and has to be achieved within 100 seconds of running the program on the simulator.

 
Note:

For comprehensive instructions on how to install and run project, please, refer to the following repo, which was used as a skeleton for this project: https://github.com/udacity/CarND-Kidnapped-Vehicle-Project

 

#### Basic Build instructions
    $ mkdir build && cd build
    $ cmake .. && make
    $ ./particle_filter

Or use the `$ bash build_and_run.sh` provided to execute the above commands.

### Final results after Particle Filter:

On the simulator: 

The grey circles are the landmarks. Blue circle is the predicted location of the kidnapped vehicle. The LIDAR and RADAR measurements(Green Lines) of the landmarks and the GPS information are used in the Particle filter program to pin down the location of the vehicle. 

The error values are displayed on the simulator screen which are the criteria to pass the project.

Running of the code on simulator:

![alt text][image1]


Success message:

![alt text][image2]


