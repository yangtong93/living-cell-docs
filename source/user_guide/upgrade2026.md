# 2026 Version Update

## Version 1.2.2-beta

Release Date : 2026/4/1

### New
* New well plate display: The processes of experiment browsing, image analysis, and image viewing all utilize the new well plate interface.
* When opening an experimental file, it displays the reading progress and supports previewing file information.
* Provide more explicit error messages when the device is abnormal.

### Fix
* Image stitching anomaly, multi-view scanning anomaly, image analysis crash, display and rendering anomaly.
* The encrypted experiment file cannot be created normally, and the same content is repeatedly displayed.
* The display related to the scale unit or objective lens is incorrect.
* Occasional communication interruptions and other issues with Lianhua SM-3 equipment.

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.2.1-beta

Release Date : 2026/1/23

### New
* Increase the calibration coefficient for UPLXAPO60XO and UPlanAPO100X objectives
* The time-series shooting module supports the setting of automatic exposure for different channels
* The vessel parameter correction function has been enhanced with a termination function
* Added function to delete expired log files
* Add video preview function
* The field of view grid supports popping up as a dialog box

### Optimize
* Optimize the pre-focus function, add a termination function, and refine the prompt information

### Fix
* Fix the discrepancy in the display of images and grids
* Fix the issue that shooting cannot be resumed after being paused in time series shooting
* Fix the abnormal function of color range
* Fixing automatic exposure is not a separate channel setting


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.2.0-beta

Release Date : 2026/1/20

### New
* SM-2 and SM-3 devices support slide and petri dish analysis, as well as related calibration functions
* Support video export of images after splicing
* Add automatic pre-focus function
* Chinese-English translation
* Beautify UI

### Optimize
* Optimize the effect of automatic exposure

### Fix
* Fix the issue of crashing when opening experimental files


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 1.1.2-beta

Release Date : 2026/1/8

### New
* In the local file workflow, viewing files supports the display of scanned data files
* In the local file workflow, batch selection and analysis of images are supported
* Time-series shooting supports customizable shooting channel order
* The photo album supports batch export of image files
* Exporting images and videos supports image preprocessing and field of view filtering

### Optimize
* Optimize the performance of the stitching algorithm

### Fix
* Fix the issue where the scale bar cannot be displayed on the image analysis page
* Fix the issue that the single-view image cannot be displayed on the image analysis page
* Fix the issue of abnormal focus starting point and range in multi-porous and multi-view shooting
* Fix issues related to zstack shooting in the time series shooting module

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above
* OpenGL 2.1 or above
* Some modules require license authorization to be used