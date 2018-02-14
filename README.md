# Xray Vision

<!-- https://raw.githubusercontent.com/TriviTran/Drone-Motion/master/README.md --->

![N|Solid](https://github.com/jayala-29/xray_vision/blob/master/xraypic1.png)

# Overview
Augmented Reality (AR) presents many opportunities for advancement in the medical research community for patient specific treatment. One of the many clinical applications of AR is in Minimally Invasive Surgery (MIS). AR enables the possibility of superimposing preoperative MRI or CT scans onto the surgical environment in vivo in order to provide guidance to the surgeon during surgery. In order to advance research in this area, we need “ground truth 3D data”. This ground truth data will allow developers to have a ground truth point to point mapping in the tissue surface from frame to frame. This will encourage further development of AR algorithms in this space, because developers will be able to evaluate the accuracy of their implementation relative to a “gold standard”.


# Group Members

  - Nelson Ho 
  - Canzhen Zhou 
  - Xiangyu Bi
  
  - Trevor McCleery 
  - Vincent Tierra 
  - Jessy Ayala
  
  
# Technology Used

## RealSense Camera

Intel® RealSense™ technology supports a wide range of operating systems and programming languages. The Intel® RealSense™ SDK enables you to extract depth data from the camera and use the interpretation of this data in the platform of your choice. Developer tools will be available in Windows* OS, Linux*, Mac* OS, and more.

# Milestones and Deliverables

Jessy Ayala
Get Realsense camera to work with hardware provided: 
Status: Completed -- 26 January 2018
Deliverable: Dummy meshes collected from camera and displayed in Meshlab.
(first mesh of dummy scan): https://github.com/jayala-29/xray_vision/blob/master/scan1trevor.png 
Develop a formal specific procedure for data analysis: 
Status: Completed -- 7 February 2018
Debugging Meshlab/Meshmixer when necessary with mesh files
Running data through the pipeline of scripts developed by the other subteam of the project and the general outputs of those specific filters (documentation)
Deliverable: A document containing step-by-step instructions for data processing and a type of guide for using mesh based computer tools. Will be continuously adjusted and updated. 
https://docs.google.com/document/d/17KMw9fFUo-SyKEaU_YaVBbyhU273UJ4z3vM2Qtg3OQ0/edit?usp=sharing 
Establish web presence: 
Status: Completed -- 14 February 2018
Deliverable: Type of online reference containing information and specifications about our project.
https://github.com/jayala-29/xray_vision 
Create a reference for processed data to reflect updated algorithms: 
Status: In-Progress -- 21 February 2018
Running data through the pipeline of scripts developed by the other subteam of the project (data results)
Deliverable: Various displays of segmentation process. Will be continuously adjusted and updated to reflect progress throughout the quarter. 
Create a reference for processed data to reflect updated algorithms: 
Status: In-Progress -- 28 February 2018
Running data through the pipeline of scripts developed by the other subteam of the project (data results)
Deliverable: Various displays of global process. Will be continuously adjusted and updated to reflect progress throughout the quarter. 
During the rest of the quarter, I plan to provide detailed documentation of the status of the algorithms and updated scans. For a challenge, I have been assigned to try to recreate the front end of the stapler tool being used in the scans. Furthermore, these are my criterion for grades:
Complete milestones 1-3 and have no/very little documentation for milestones 4-5. 
If I do this, give me an B.
Complete milestones 1-3 and have some documentation for milestones 4-5. 
If I do this, give me an B+.
Complete milestones 1-3 and have heavy documentation for milestones 4-5.
If I do this, give me an A-.
Complete milestones 1-3 and have heavy documentation for milestones 4-5. Along with this, a successful laser scan of part of the stapler tool that can be used for segmentation.
If I do this, give me an A.
Nelson Ho
B - Develop the code to perform segmentation of rigid and nonrigid portions of scan data. 
Complete by: Feb 1, 2018
Modify global registration code to output a single result for global registration, as well as a list of point correspondences relating input points to points in the global model. 
Status: Jan 26, 2018
Write scripts to relate points in global registration to the point in the original mesh.
 	
Work on MICCAI paper. 
Status Feb 23, 2018
Trevor McCleery
Develop a specific procedure for data collection: 
Status: 15 February 2018 
Specific operation of computer/camera interface: how scripts are run, which laptop to use, which USB ports will work with camera.
Detail of how camera will be mounted and positioned for recording. The goal is to create a documented, repeatable procedure that can be referenced when analyzing the quality of the data recorded. 
Deliverable: A document containing step-by-step instructions of the data collection process. This is important to document how data is collected for these ground truth data sets. The procedure must be repeatable and able to accommodate adjustment to individual steps as necessary.
Record porcine liver on site at the Center for the Future of Surgery (CFS)
Status: completed 7 February 2017
Deliverable: A set of 13 recordings of the porcine liver with various lighting configurations. On the day of the recording, Michael, Trevor, and Vincent traveled to the CFS and performed a series of recordings on a living pig. The pig was sedated, and prepared for operation by the medical staff. Between surgeries, we were able to perform our recordings using the surgical lighting provided in the operating room. The lighting was adjustable by angle and position, but not by intensity. Therefore, the various lighting conditions we could provide were always full intensity, which sometimes created shadows when not pointing directly at the subject. 

Looking forward, I will be focusing my efforts on two primary tasks:
Perform a secondary recording at the CFS. Using feedback from the segmentation/registration team and familiarity with the equipment and venue, a valuable set of second recordings can be obtained. If I do this, give me an B.
Make improvements to the Python recording script by added command line options that will allow the user to adjust camera parameters by passing an argument at the command line. If I do this, give me a A.
Improving the quality of the scans. Some recordings showed noise and distortion when viewed off axis. This could be due to the camera’s settings, of which the documentation is not readily accessible. It may be that the camera cannot provide the quality of data required. If so, we intend to determine that definitively. 



Vincent Tierra
Create an instruction manual for the recording apparatus for the data collection: 
Status: In progress - Due date February 15, 2018
Detailed steps with how to setup the computer and camera needed to collect video recordings
Deliverable: An instruction guide with steps on how to setup the camera and how to run the scripts in the computer and some technical issues with the camera and how to resolve it.  
Make an appointment at the Center for the Future Surgery (CFS) to conduct recordings  and do recordings of the pig’s liver at the surgery site. 
Status: Completed February 7, 2018
Deliverable: A recording of the pig’s liver at the CFS with various angles and lighting. 
Google drive link to the recordings:
https://drive.google.com/drive/folders/1-OOP0Wo8JggQuUAvSluBppixM2xEYloo?usp=sharing (must have a ucsd email to view it)

Since we have done the first recording of the pig’s liver at the surgery site, the next step in this project is to improve the quality of the scans, currently there are still some noise in the recordings. This could be due to a variety of different things; the camera settings, lighting, or the camera itself. We definitely want to conduct a 2nd recording, however, this part might be tricky because setting up an appointment (schedule) at CFS is challenging but if we manage to get another appointment and do a second set of recordings with valuable data, I would like to get a B. We will try to mimic the light intensity of the surgical lights and try different camera settings to see if we can get a better recording. To get an A in this class we will work on the UI on the script for the realsense camera to make it more robust and versatile by having the option to pass in the parameters in the command line to change the camera settings, and document this step, and also by completing milestone 1 & 2.

Xiangyu Bi
Objective: Finishing the technical programming and debugging part of computer vision algorithm validation and optimization. The current benchmarks are broken or might not be applied to our liver dataset. We need to modify or rewrite some parts of the codes to make it work on the surgical dataset collected by other teammates.

Schedule:
Theoretical preparation for the project, including ICP algorithm, non-rigid global registration algorithm etc. Go over the segmentation code and global registration benchmark. 
Status: Completed 17 January 2018	
2. With the collected test dataset, run through and get familiar with details of segmentation and global registration benchmark, fixing potential bugs. 
Status: Completed 30 January 2018
	      In detail, we found some problems during the progress of going over the benchmark. 
  Some bugs in the current segmentation code. The liver segmentation process 	can be divided into several steps. First we manually segment the rigid part from the first scan. Then for the next scan, we use algorithm to build match between the segmented rigid part and the current scan, which means roughly the corresponding points in the current scan are found. Next do a geometric search around those points thus all the rigid region can be included. Finally we cut it off as the rigid part to match for the next scan. Iteratively all the rigid parts in the scans can be segmented. We found the current segmentation always use the first scan as the rigid template. We fixed that to make the iterative one work.
The main issues during segmentation, which are about “match” and “search”. The search radius is of great significance. Using too small radius will make the rigid point cloud really sparse and some noise will be left to cause global registration confusing. Conversely, segmentation performance is more sensitive to large radius, because sometimes rigid part and nonrigid part get really close in the scan, when searching around these occlusion parts, large radius would count some nonrigid points as rigid part. On this condition the rigid part will get exploded with iterative steps. We have tried for a proper radius one by one with step size of 0.001. Now we can get a comparatively good result, however the  problem cannot be resolved completely.  The “match” algorithm is really sensitive to the datasets. Sometimes it got failed to match between two scans. Since we only collected two sets of data to test the performance, we cannot find exactly what features to make the match failed. Most of time it worked well.
Deliverable: Canzhen and me collaborated with each other to debug and modify the code. We saved the processed file as *.ply on the server, also cut gif images to illustrate how the segmentation benchmark works. To avoid overlap, they will be shown in Canzhen’s work.
3. Preprocessing liver dataset, collaborating with data-collecting dataset, to make the       benchmark work.  
Status:  In progress	
	      Details about working with surgical liver data.
Segmented the red liver portion from the scan. The surgical data we collected last week is, on the intuition, not ready for segmentation and registration, since the liver part we need to use is comparatively small in the whole scan. We need to write scripts to cut the valid part and mitigate the noise.  Since scans are taken with fixed camera angle, so we can use geometric features to extract liver points roughly. With proper x, y and z coordinate threshold the entire liver part can be segmented. However, the segmented part shown in meshlab is somewhat darker than the original one. We think it should be caused by some display problems, which we need to figure out.
Deliverable: The liver scan we got and some attempts to cut it off.

4. Improve the performance of the algorithm, to make the result of liver dataset better. March 6, 2018

Milestone -B
Going over current benchmark.
Fix some bugs in segmentation and registration work. Up to now the segmentation code is much better than the former broken one. It means to get a B I only to find some possible functional flaws in the registration code and repair to make the workflow run.
Milestone -A
Finish Milestone B
For segmentation code, make it more robust and suitable for our surgical application, which means it can segment the liver data more reliably.
For global registration. We cannot run it perfectly for any dataset right now. We need to achieve the goal of nonrigid registration in the liver dataset and deliver successful results constructed.
Milestone -A+
Finish Milestone A
Do some optimization about the algorithm to improve the performance, such as we can add more features for the points, like colors. However the current benchmarks are packaged and all information about color is not saved, there is a long way to go to achieve this.

Canzhen Zhou
Set up the environment. January 16, 2018
Run through the segmentation code with the test image. January 31, 2018
Run through the registration code with the test image. February 8, 2018
Run through the segmentation code with collected liver image. February 15, 2018
Run through the registration code with collected liver image.  February 25, 2018
Fix the possible bugs. March 5, 2018
Improve the registration code with more dimensions, for example, adding colors. March 10, 2018

Requirement of Grade
If I do milestone 4 I get B+, if I do milestone 5 I get A, and if I do milestone 6 or 7, I get A+.

Update of Milestone
I change the order of the task. Previous order is running through all the segmentation code part and then run the registration part. However, we went through the segmentation code quicker then we expect, the liver image data went a little slower. So we move on to the next stage of running registration code with the test image.
So I switch the “run through segmentation code with liver image” with “run through registration code with test image”.

Completed
Created a our own development server, equip the server with the environment of running C code.

a snapchat of server environment that is able to 
run the script of segmentation and global registration
Completed
The steps of running through the segmentation code are as follows:
Use /home/nelsonho/convertToMesh.py to convert the scanned '*.ply' file to convert all the point clouds that were collected from the real sense to meshes. Notice that convertToMesh.py and doNothingScript.mlx should be in the same directory.
Pick one '.ply' scan image, open it in MeshLab, export it as '.obj' file.
Open the '.obj' file in MeshMixer, click on 'Select', select the rigid part (could be arms or something else), and choose 'Edit -> Seperate', and the export the rigid part as '.obj' file.
Use /home/nelsonho/convertToObj.py to convert all the '*.ply' file (already converted to meshes) to '.obj' file so that the segmentation code would take in.
Open the code liverscansegmentation, build the code, create the environment
cd [coderoot]
mkdir build
cd build
cmake ../src-ICP-benchmarks
make
the executable sparseicp should be created in the build directory
Run the script to segment all image
./sparseicp --source <pre-segmented tool (.obj) from first scan in sequence> --scan-dir <directory of scans to be segmented ordered alphanumerically> --result-dir <output directory>

Revise the milestone with “Walking through the process of global registration code”
The steps of running through the global registration code are as follows:
Include following directories in your path:
[globalnrregistrationbaseline coderoot]/trimesh2/bin.Linux64
[globalnrregistrationbaseline coderoot]/tps_alignment/bin.Linux_nocona
Place ply’s for nonrigid alignment in the nonrigid/ directory
Place ply’s for rigid alignment in the rigid/ directory
Run the run.sh script
