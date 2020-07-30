# Landmark Detection & Robot Tracking (SLAM)

This repo contains  project 3 of Udacity Computer Vision Nano Degree( CVND ) .

## Project Overview

In this project, you'll implement SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! You’ll combine what you know about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems. 

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using *only* sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.*

<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>

The project will be broken up into three Python notebooks; the first two are for exploration of provided code, and a review of SLAM architectures, **only Notebook 3 and the `robot_class.py` file will be graded**:

__Notebook 1__ : Robot Moving and Sensing

__Notebook 2__ : Omega and Xi, Constraints 

__Notebook 3__ : Landmark Detection and Tracking 


### Local Environment Instructions

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/parvez218/Project-Landmark-Detection-Tracking-SLAM-.git
cd Project:Landmark Detection & Robot Tracking ( SLAM )
```

2. Create (and activate) a new environment, named `cv-nd` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n cv-nd python=3.6
	source activate cv-nd
	```
	- __Windows__: 
	```
	conda create --name cv-nd python=3.6
	activate cv-nd
	```
	
	At this point your command line should look something like: `(cv-nd) <User>:Project:Landmark .. <user>$`. The `(cv-nd)` indicates that your environment has been activated, and you can proceed with further package installations.

You will be required to install ''' numpy ''' and '''matpotlib'''


## Notebooks

1. Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```shell
cd
cd Project:Landmark Detection & Tracking(SLAM)
```

2. Open the directory of notebooks, using the below command. You'll see all of the project files appear in your local environment; open the first notebook and follow the instructions.
```shell
jupyter notebook
```

3. Once you open any of the project notebooks, make sure you are in the correct `cv-nd` environment by clicking `Kernel > Change Kernel > cv-nd`.


### LICENSE

 This project is licensed under the terms of the MIT license.
