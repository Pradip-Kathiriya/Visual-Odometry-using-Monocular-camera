## Project Description

The objective of this project is to utilize visual odometry on a sequence of video frames captured by a monocular camera to estimate the trajectory of a 
vehicle. The KITTI dataset is employed for this purpose, which comprises two monocular videos, an intrinsic camera matrix (K), and the vehicle's ground 
truth pose. The ground truth information is leveraged to assess the efficacy of the visual odometry.

## Pipeline

![mono_vio](https://user-images.githubusercontent.com/90370308/221735805-6971e5c7-9878-42cd-80b5-c7f28d0393be.png)


## Result

### Input video

#### Sequence 1

![input](https://user-images.githubusercontent.com/90370308/221733482-bf52fa93-6e88-49d7-85ad-5e9dfa69a647.gif)

#### Sequence 2

![input](https://user-images.githubusercontent.com/90370308/221734289-478ffc1d-c88a-44a6-88e7-11bffc9ed62e.gif)


### Detected Feature

#### Sequence 1

![feature](https://user-images.githubusercontent.com/90370308/221733805-5f558365-ea0b-4bcb-a73d-9e8961f64cee.gif)


#### Sequence 2

![output](https://user-images.githubusercontent.com/90370308/221734247-7e0901c8-c5ae-44bc-91bc-2548c861adf1.gif)


### Estimated Trajectory

#### Sequence 1

![plot](https://user-images.githubusercontent.com/90370308/221735068-aff7ee7b-254c-474c-a708-8dedce6de74b.png)

#### Sequence 2

![path](https://user-images.githubusercontent.com/90370308/221735641-f8d10f8c-ec0e-45dd-80af-1f93c33b1bc6.png)







