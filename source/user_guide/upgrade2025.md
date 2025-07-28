# 2025 Version Update

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
