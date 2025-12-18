# 2025 Version Update

## Version 1.0.9-beta

Release Date : 2025/12/17

### New
* Real time preview and time series shooting with added hole pre focus function
* Time series shooting supports 2D image stitching

### Fix
* Re calibrate the correspondence between the objective lens and the scale bar
* Analyzing image collapse issues without adjusting brightness and contrast
* Fix the issue of overlapping rate errors in image stitching
* Fix the time-consuming process of generating masks
* Multi point multi view shooting, first capture multiple channels of a single view, and then move to the next view
* Fix SM-2 coordinate movement anomaly issue
* Fix the problem of incorrect orientation of spliced images
* Fix one click multi-channel crash issue

### Optimize
* Optimize path planning for real-time preview view scanning

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used


## Version 1.0.8-beta

Release Date : 2025/12/10

### New
* Support SM-3 devices
* Add analysis page related functions
* Add functions related to viewing image pages
* Time series shooting supports automatic focusing at intervals of N fields of view
* Time series shooting supports execution analysis and display analysis results

### Fix
* Fix the problem of inaccurate coordinate calculation of holes and field of view
* Fix ZStack parameter calculation error issue

### Optimize
* Optimize the schematic display module of the orifice plate

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used


## Version 1.0.7-beta

Release Date : 2025/11/20

### New
* Add zoffset interface and functionality, suitable for one click multi-channel shooting and time-series shooting
* Multi point multi view shooting supports multi-channel selection and execution
* Time series shooting supports scanning devices for multi view shooting

### Fix
* Multi point multi view shooting does not automatically focus by default
* Fix the crash issue after modifying camera parameters

### Optimize
* Optimize the accuracy of vessel calibration
* Optimize the scope of the internal frame


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.6-beta

Release Date : 2025/11/13

### New
* Add auxiliary lines for vessel calibration
* Store and read autofocus parameters
* Increase the gamma, brightness, and contrast adjustment functions of the camera
* Add the function of holding down the right mouse button and dragging to move the field of view
* Add the function of moving the field of view up, down, left, right with buttons
* Add mouse double-click to move the field of view to the center position on the screen

### Fix
* Fix the issue of inconsistent reading values in parameter templates
* Fix zstack parameter calculation error
* Resolve issues related to multi-point shooting
* Fixed the issue of incorrect display of multi-point captured images in the album
* Fix the issue of device configuration page crashing when entering DD-2
* Fix the problem of Z-axis roller movement function failure

### Optimize
* Modify default shooting parameters


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.5-beta

Release Date : 2025/11/6

### New
* View image page, add image/video file export
* Real time preview page, adding scale bar and unit display
* Real time preview page, added autofocus parameter setting function, autofocus stop function
* Real time preview page, adding video recording, snapshot export, and album functions

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.4-beta

Release Date : 2025/10/31

### Fix
* Fix histogram adjustment display error
* Fix inability to access time series shooting page
* Flip the screen of SM-2 left and right

### Optimize
* Optimize one click multi-channel shooting
* Optimize light intensity, gain, and exposure time adjustment functions
* Optimize XY movement


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.3-beta

Release Date : 2025/10/29

### New
* The analysis page supports scanned data sources

### Fix
* Improve the support of SM-2 equipment for orifice plate vessels
* Fixed the issue of running termination after enabling auto focus in time series shooting
* Fix the issue of switching channel Z-axis to zero
* Repair occasional Y-axis failure issue of SM-2 equipment

### Optimize
* Optimize 2D stitching algorithm

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.2-beta

Release Date : 2025/10/24

### New
* Real time preview page adjustment interface.
* Real time preview page adjustment of most functions, such as effect settings, ZStack， Objective lens switching, XYZ axis setting, channel switching, automatic mode, manual mode.
* View the image page to display the image of the porous plate taken.
* Add scanning version device model SM-2.
* Time series shooting supports multi-stage operation with a single field of view.

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.0-RC1

Release Date : 2025/10/13


### Fix
* Fix the crash issue when entering the device configuration page

### Optimize
* Optimizing the calculation of autofocus starting point during time series shooting process
* Add a new way to obtain hardware information

### Notes
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.1-beta

Release Date : 2025/9/22

###  New
* Vessel selection supports glass slides, well plates, and culture dishes
* Add manual and automatic modes
* Add the function of editing orifice plate information
* Increase the management of utensils and consumables
* Vessel calibration supports glass slides, well plates, and culture dishes
* XY axis control, supports field of view navigation and positioning, joystick movement, up, down, left, and right buttons to move the field of view, mouse drag to move the field of view.
* View, hole supports single selection, multiple selection. Copy and paste the view between holes.
* View recording, save view, click to move view.
* One click multi-channel shooting, exporting shooting results.
* Multi view and multi-point shooting function, supporting two position stitching, Z-Stack， Auto focus is optional.
* Setting and Display of Overlapping Field of View
* Add album function to preview captured images
* Scale supports fixed length
* Time series shooting, supporting millisecond level shooting intervals


### Optimize
* Optimize the jumping logic between pages

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.0.0

Release Date : 2025/9/28

###  New
* Add Galaxy_2Window_CN_32bits-64bits_2.4.2504.9091.exe to the installation package
* License application supports setting expiration time according to module settings
* Limit the input range of Z-Stack parameters
* New prompt for repeatedly opening processes
* Add writing of complete dump file
* Auto focus is offset according to z-offset

### Fix
* Fixed the issue of mask not being cleared after switching algorithms
* Fix Z-Stack preview related issues
* Fix Z-axis calculation errors in time series shooting

### Optimize
* Optimize the accuracy of autofocus algorithm
* Optimization of Z-axis adjustment usage
* Optimize the usage process of parameter templates

### Notes
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.6.8-RC

Release Date : 2025/7/24

###  New
* Support different Z-axis movement ranges for different objective lens configurations
* Real time preview supports partial scanning version function

### Fix
* Fix control issues related to DD-2 devices
* Fixed the issue of abnormal shooting process after enabling Z-Stack for time series shooting
* Fix the issue where advanced cell analysis cannot be used
* Repair batch scratch analysis function abnormality
* Fix that autofocus cannot be manually stopped

### Optimize
* Improve autofocus accuracy
* The exposure gain range is uniformly from 0 to 10
* Optimize the Z-axis user experience
* The convergence degree of advanced cell analysis has been changed to the initial version
* Optimize video recording memory usage
* Optimization of User Parameter Template Process



### Notes
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.6.7-beta

Release Date : 2025/6/17

### Optimize
* increase Z-axis position in the parameter template
* Plugin loading failed, can choose to skip

### Fix
* Fix the status display after file loading
* Fix DD-1 device unable to open issue

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.6.6-beta

Release Date : 2025/6/16

### New
* Real time preview, supports exporting images with multi-channel fusion
* View the file page and display the shooting parameter information of a single image
* Added autofocus algorithm
* Add DD-2 and SM-1 equipment control
* Real time preview page, adding XY movement control
* Support Z-axis position settings for different channels for time series shooting

### Optimize
* Enhancement of objective lens module
* Optimize parameter templates
* Mask parameters are saved/loaded according to different analysis methods
* Real time preview, when switching objectives, it will be linked to switch Z-axis position, light intensity, gain, exposure time, etc.

### Fix
* Fix the issue of inconsistent histogram parameters between the real-time preview page and the image viewing page
* Fix occasional serial communication failure issues

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.6.4-beta

Release Date : 2025/4/8

### Fix
* Fix the issue of mask adjustment crashing
* The default time interval mode is selected for experimental settings
* Fixed the issue of being unable to proceed to the next step after importing the local image file
* Fix the image/video of the exported fluorescence channel with image enhancement effect

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.6.3-beta

Release Date : 2025/4/7

### New
* Add a neural tracking analysis module.
* Add automatic settings and adjust the color range in the real-time preview page
* Reset relevant interfaces and functions between different samples

### Fix
* Fix the issue of inaccurate analysis progress bar
* Fix the crash caused by the mismatch between the default configuration obtained and the actual configuration
* Fix image display anomalies in multi view situations
* The file has not been fully loaded, restricting access to the next step
* The experiment name cannot be repeated
* Invalid image deletion repair, in the real-time preview page,


### Optimize
* Optimize file loading
* During the time series shooting process, analysis failure will not stop the task
* Scratch healing rate supports setting decimals
* Verify the parameters of time series shooting
* Optimized the parameter storage for channel effect adjustment


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.6.2-beta

Release Date : 2025/3/12

### Fix
* When switching between different experimental files, the previous state was not cleared.

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.6.1-beta

Release Date : 2025/3/12

### New
* The left page in the analysis page supports floating
* Real time preview and viewing of the left page of the image page, supporting automatic tiling.
* Analyze data export, add a dialog box to select whether to export image files with masks.
* The Z-Stack preview page defaults to displaying the image of the first channel.

### Fix
* Image processing did not participate in the export process
* The problem of fluorescence transfection efficiency not being displayed
* RWD value display error in scratch analysis
* Fix the time series shooting crash caused by abnormal Z-Stack settings
* Taskbar progress status not restored
* Real time preview page, equal color range leads to abnormal display

### Optimize
* Brightness and contrast are not saved by default
* The performance of image preprocessing and Z-Stack algorithm has been optimized.
* Simulate device module, supporting loop reading of image files in the directory.


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used


## Version 0.6.0-beta

Release Date : 2025/2/22

### New
* Most pages have added the function of saving and restoring user parameters
* Analyze the channel adjustment page on the page and add a restore function.
* Video export page, adding video preview function
* View image page, add preview Z-Stack function
* The results and adjustment effects of image preprocessing, participate in the subsequent analysis process
* Image viewing page, added automatic calculation of color mapping range

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.5.7-beta

Release Date : 2025/2/11

### New
* Add Transfection Efficiency indicator
* Analyzing data export will export image files with masks


### Fix
* When the scale bar is dragged outside the image, scaling will affect the centering display.


### Optimize
* Double click the scale bar to adjust color, opacity, and width.
* Reduce the time consumption of image/video export function

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used


## Version 0.5.6-beta

Release Date : 2025/1/24


### Fix
* Fix the automatic calculation of mapping range for bright field images
* Fix AVI video frame abnormality issue
* Fix the issue of blurry images in MP4 videos


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.5.5-beta

Release Date : 2025/1/23

### New
* Analysis parameters can restore default values
* Add background correction function
* Image enhancement and background correction are only effective for bright field images
* Add video recording function
* Real time preview page adds snapshot export function
* All captured images are automatically saved in TIFF format in the designated folder
* Add SA-40X objective lens


### Fix
* Fix the captured image that is not suitable for the color range
* Fix that contrast and brightness cannot be applied to exported images
* Fix the issue of incorrect display of exported video time
* Fix the issue of incomplete deletion of analysis records
* Fix the issue where the 4X and 40X objective lenses cannot be selected

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.5.3-beta

Release Date : 2025/1/14

### New
* Add A-4X objective lens
* Display the status of experiment file loading failure
* New device connection status and open/close status display
* Add a secondary confirmation dialog box for exiting the program
* Automatically obtain the latest license status at regular intervals
* Export ZStack image with pseudo color

### Fix
* Fix the issue of inaccurate calculation of remaining time in the experiment run
* Fix the issue of incorrect calculation of the quantity of exported ZStack
* Fix the issue of unable to interrupt the process of exporting ZStack
* Fix the issue of abnormal crashes caused by stopping experiments
* Fix the issue where exported AVI format videos cannot be played


### Optimize
* Optimize the loading speed of export pages and image selection pages


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used



## Version 0.5.2-beta

Release Date : 2025/1/7

### New
* Some pages add pseudo color mapping
* Time series shooting adds warning information for all black or all white images

### Fix
* Fixed the issue of incorrect image switching between different channels on the detailed page of the experiment run
* Prevent screen shaking caused by multiple resets

### Optimize
* Modify the default mask color


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used
