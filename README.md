# EVT_EKF
In this we recursively estimate the position of a vehicle along a trajectory using available measurements and a motion model.  The vehicle is equipped with a very simple type of LIDAR sensor, which returns range and bearing measurements corresponding to individual landmarks in the environment. The global positions of the landmarks are assumed to be known beforehand. We will also assume known data association, that is, which measurment belong to which landmark.

![EKF Trajectory](https://user-images.githubusercontent.com/83055325/182040505-b2998ddd-dab1-468a-933f-a74e20b6aa13.jpg)
