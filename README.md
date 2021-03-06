# Unscented Kalman Filter Project Code

This is the project for Self-Driving Car Engineer Nanodegree Program. The codes are already compiled.
The results are also visulized.


---

## Dependencies

* cmake >= 3.5
 * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./ExtendedKF path/to/input.txt path/to/output.txt`. You can find
   some sample inputs in 'data/'.
    - eg. `./UnscentedKF ../data/sample-laser-radar-measurement-data-2.txt output.txt`

## Results
1. run against "sample-laser-radar-measurement-data-1.txt". 
   -  `./UnscentedKF ../data/sample-laser-radar-measurement-data-2.txt output.txt`
   -  Accuracy - RMSE:  **[0.0719835, 0.0792645, 0.585835, 0.573825]**
   -  Visulization:
    `Modify txt file name in /CarND-Mercedes-SF-Utilities-master/python/ekf-visualization`
    ![alt text](https://github.com/shangliy/CarND-Unscented-Kalman-Filter-Project/blob/master/results/data1_img.png?raw=true)
   -  NIS:
     ![alt text](https://github.com/shangliy/CarND-Unscented-Kalman-Filter-Project/blob/master/results/data1_NIS.png?raw=true)

1. run against "sample-laser-radar-measurement-data-2.txt". 
   -  `./UnscentedKF ../data/sample-laser-radar-measurement-data-2.txt output.txt`
   -  Accuracy - RMSE:  **[0.192707,0.190921, 0.407995, 0.51259]**
   -  Visulization:
    `Modify txt file name in /CarND-Mercedes-SF-Utilities-master/python/ekf-visualization`
    ![alt text](https://github.com/shangliy/CarND-Unscented-Kalman-Filter-Project/blob/master/results/data2_img.png?raw=true)
    -  NIS:
     ![alt text](https://github.com/shangliy/CarND-Unscented-Kalman-Filter-Project/blob/master/results/data2_NIS.png?raw=true)
     
