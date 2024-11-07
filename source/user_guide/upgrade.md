# Version Update Notes

## Version 0.3.8-beta

Release Date : 2024/11/7

### New
* Support batch analysis and single analysis
* Add image and text explanations for the analysis module
* Add the function of reapplying for licenses
* Image export supports canceling interrupt process

### Fix
* Resolve the issue of unreleased resources after the experiment is completed
* Fix the issue where the opacity of the filling cannot be adjusted upwards


### Optimize
* Optimize the loading speed of experimental files
* Adjust the shooting interval between channels to 1 second

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.3.7-beta

Release Date : 2024/10/31


### Optimize
* Optimize the loading speed of experimental files

### Fix
* After switching channels, the automatic exposure status is incorrect

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.3.5-beta

Release Date : 2024/10/24

### New
* Change the software name from `CellLiving` to `CellPerception`
* Add functions related to hardware parameter templates
* New email for warning method
* Add a special effect of flashing during shooting
* Video export supports MP4 format

### Optimize
* Reduce the sensitivity of memory alerts

### Fix
* Run the command to return the X-axis to the origin only in a multi lens configuration

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.3.4-beta

Release Date : 2024/10/18

### Fix
* Fix the issue of incorrect command for returning X-axis to origin

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.3.3-beta

Release Date : 2024/10/17

### New
* The installation package can choose whether to install USB and camera drivers
* The batch analysis function is executed according to the parameters set by the user
* Added warning function, including alerts for confluence and wound heal rate
* Add the function of returning the X-axis to the origin, after the device is successfully started.


### Optimize
* Serial communication, adding timeout mechanism to prevent infinite waiting
* The maximum range of hole in basic cell analysis has increased from 2000 to 5000


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.3.2-beta

Release Date : 2024/10/12

### New
* Add the function of pausing and resuming experiments

### Optimize
* Optimize the file list reading process
* Optimize the process of creating experimental files
* Improve the stability of experimental operation


### Fix
* Fix the issue of inaccurate shooting times in ZStack
* Fix the issue of invalid video speed settings
* Fix scratch analysis input parameter errors


### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.2.0-RC4

Release Date : 2024/9/29

### Fix
* Fix the issue of ineffective video playback speed

### Notes
* This is a candidate version that may have a few bugs
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.3.1-beta

Release Date : 2024/9/27

### New
* Add prompts to prevent users from switching pages when autofocus or ZStack is not completed
* Exporting images allows you to choose whether to include scale units or not

### Fix
* Fix the issue of ineffective shooting based on the total duration
* Resolve the issues caused by concurrent and out of order tasks during time series shooting
* Resolve the issue of exporting TIFF format files that do not support Chinese paths

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.3.0-beta

Release Date : 2024/9/26

### New
* Add the function of checking and prompting disk space on the experiment schedule page
* Regularly check the available size of memory and disk, and prompt if it is less than 1GB
* New shooting progress for ZStack


### Optimize
* Scratch analysis fills small impurities in the scratch area
* Optimize the operational process of time series shooting
* Optimize the running process of batch analysis tasks
* In ZStack shooting, prioritize capturing the channels before moving the Z-axis


### Fix
* Fix inaccurate eccentricity in basic cell analysis.
* Fix the issue of inaccurate average fluorescence intensity in basic cell analysis.

### Notes
* This is still a beta version and may contain many bugs.
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.2.0-RC3

Release Date : 2024/9/13

### New
* Exposure gain supports decimal adjustment
* Export images and videos with time, preprocessing, and scale bar
* Exporting videos supports Chinese paths

### Optimize
* The analysis page only analyzes the images of the channels selected by the user
* Optimize the loading process of experimental files

### Fix
* Resolve the issue of the image selection page leaving the previous items
* Objective lens switching should not be performed when the device only has one objective lens
* Fix analysis cannot be deselected issue
* Fix the issue of abnormal overlay image effects
* Fixed the issue of only displaying single channel analysis results when enabling ZStack and setting up multi-channel shooting in the experimental settings
* Fixed the issue where the preprocessing state was not reset when switching between different files
* Fix the issue of displaying channels that have not been captured, in the export dialog


### Notes
* This is a candidate version that may have a few bugs
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.2.0-RC2

Release Date : 2024/9/4

### New
* Added simulation image setting function, in debugging mode

### Optimize
* Optimization analysis results display proportion

### Fix
* Fix program crashes in some operating systems
* Fix the issue of inconsistent brightness between the preview image and the original image


### Notes
* This is a candidate version that may have a few bugs
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.2.0-RC1

Release Date : 2024/9/2

### New
* Add overlay image display to some interfaces
* Add the function of storing abnormal information after program crashes


### Optimize
* Reduce CPU usage for loading experimental files

### Fix
* Fix the issue where the experiment cannot be stopped
* Fix issues related to ZStack position adjustment
* Fix the crash issue caused by inconsistent running environment of image preprocessing
* Fix the issue with setting the experimental time interval
* Fix the issue of excessive brightness in the overlay display effect


### Notes
* This is a candidate version that may have a few bugs
* Only supports Windows 7/10 (x64) or above  
* OpenGL 2.1 or above
* Some modules require license authorization to be used

## Version 0.1.3-beta

Release Date : 2024/8/28

### New
* Added the function of adjusting the width of mask lines
* Add parameter interface for scratch experiment adjustment
* Add the function of exporting experimental analysis data as files
* Added scale bar display for exported images
* The analysis result table supports copying analysis data to the clipboard
* Add 2 new parameters in the basic cell analysis module

### Optimize
* Optimize the basic cell analysis
* Optimize the loading process of experimental files
* Optimize the effect of image overlay
* Optimize the display performance of masks

### Fix
* Fix the issue of incorrect calculation of start time, interval, and end time on the experimental settings page
* Fix file recognition issue caused by Chinese path
* Fixed the issue where a single shot cannot export the original image of ZStack
* Fix the issue where the experiment cannot be paused
* Fix analysis data display errors
* Fix the issue of resetting the state of the mask after each analysis is completed
* Fix the problem of deconvolution crashing
* Fix full screen exception issue
* Repair scratch experiment analysis crash issue, during local file analysis process
* Fix the issue of not conducting analysis in the experiment when ZStack is enabled in the experimental settings
* Fix the issue of incorrect shooting position in ZStack


### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

## Version 0.1.2-beta

Release Date : 2024/8/16

### New
* Basic cell analysis module, supporting fluorescence channel analysis
* Add the function of reanalyzing experimental files again

### Optimize
* Optimize some UI interfaces
* Optimize the loading process of historical files
* Exposure gain adjustment increases sensitivity

### Fix
* Fix the issue of incorrect display of analysis results after switching
* Fix the issue of not updating the start time in a timely manner on the experiment schedule page
* Fix the issue where external files or directories cannot be selected
* Fix the issue of Z-axis not being set during the experiment process
* Fixed the issue of interface not adapting to size, in the multi view display multi-channel function
* Fix the abnormal display issue of the scale bar
* Fixed the issue of the device not shutting down after pausing the experiment

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

## Version 0.1.1-beta

Release Date : 2024/8/6

### New
* The basic cell analysis module uses new algorithms
* Add 2 objective lenses
* The analysis results are converted from pixel units to physical size units
* Improve Z-Stack functionality and add export and storage functions
* Add the function of importing serial image files
* New scale, shortcut key `P` can modify the width, color, and opacity.
* Add multiple views to display images from multiple channels separately
* Time series shooting supports Z-Stack

### Optimize
* optimize multi-channel overlay display effect


### Fix
* Fix the issue of program crashes caused by entering content in the comment input box

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

## Version 0.1.0-beta

Release Date : 2024/7/24

### Fix
* Fix the issue of not generating experimental files

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

## Version 0.0.9-beta

Release Date : 2024/7/24

### New
* Add `RWD` for Scratch Experiment
* Add video export function
* Add the function of deleting analysis results
* Add automatic exposure function
* Preview page supports modifying the autofocus starting point
* New feature for restoring color mapping settings
* Add image deconvolution

### Update
* The minimum exposure gain value has been changed from 10 to 1
* Change the scalar range of the color mapping to 0-255
* Invalid analysis results not displayed

### Optimize
* Accelerate local file reading
* Turn off the lights when leaving the preview page

### Fix
* Fix the issue of interface not changing when switching images
* Fix the issue where the color mapping scalar range does not take effect after modification
* Fix the inconsistency between the overlay effect of exported images and the interface display
* Fix the issue of failed import of external tif format image files
* Fix crash caused by local file read failure

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

## Version 0.0.8-beta

Release Date : 2024/7/18

### New
* Add scratch experiment in analysis page.
* Time series shooting supports analysis function
* Add license module
* Add sequence file analysis function
* Automatically store and import experiment files
* Add the function and page for viewing experiment files


### Optimize
* Optimize image contrast and brightness adjustment functions

### Fix
* Fix the issue where the 'Stop Autofocus' does not take effect
* Fix occasional data reception issue with serial communication module

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

## Version 0.0.7-beta

Release Date : 2024/7/3

### Fix
* Fix background color error issue on the analysis page

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

## Version 0.0.6-beta

Release Date : 2024/7/3

### New
* Image export function adds multi-channel fusion method
* Add 3 image preprocessing functions
* Implement UI for partial pages

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above


## Version 0.0.5-beta

Release Date : 2024/6/28

### New
* New basic/advanced cell analysis for single shot
* Add external regular format image import, such as png, jpg, tif
* Add Z-Stack for single shot in preview page
* New stop autofocus function in preview page
* New objective switching function in preview page
* New time series shooting and viewing of experimental process
* Supports 2D/3D rendering engine, default 2D, can be switched through the system settings page


### Fix
* Fix occasional failure of command sending function in serial port module

### Optimize
* Optimize multi-channel overlay display

### Notes
* This is still a beta version and may contain many bugs.
* Windows 7/10 (x64) or above  
* OpenGL 2.1 or above

