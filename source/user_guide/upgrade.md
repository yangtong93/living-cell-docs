# Version Update Notes

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

