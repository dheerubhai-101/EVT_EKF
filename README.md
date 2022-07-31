# EVT_EKF
In this,
we recursively estimate the position of a vehicle along a trajectory using available measurements and a motion model.  The vehicle is equipped with a very simple type of LIDAR sensor, which returns range and bearing measurements corresponding to individual landmarks in the environment. The global positions of the landmarks are assumed to be known beforehand. We will also assume known data association, that is, which measurment belongs to which landmark.

Ground Truth
If available, it is useful to plot the ground truth position and orientation before starting the assignment.
<img src =  "https://user-images.githubusercontent.com/83055325/182040917-56026abb-f52a-4ff0-b6e3-8ca9c7468fb0.png"
width="420" height="270" >

<img src =  "https://user-images.githubusercontent.com/83055325/182040924-dd376354-b999-4224-bea4-a7b2af50ab0d.png"
width="420" height="270" >


![EKF_traj](https://user-images.githubusercontent.com/83055325/182040522-156b005e-feba-4f9d-b15c-28bf85387e9e.jpg)

![EKF_orientation](https://user-images.githubusercontent.com/83055325/182040535-95db1c12-ffe7-4c40-9a89-e93cbc6fed2d.jpg)
