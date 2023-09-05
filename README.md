# iPhone-VCAM

Virtual Camera based on Cydia Substrate

# Function

Replaces the iOS camera screen.

## Software
- Supports most apps

## Supported System Versions

- Developer tested on iOS 13.3, 13.5, 14.3
- Should theoretically support iOS 11.0+
- NO iOS15+/rootless support

# Getting started

## Installation

## Use
- The following **-** symbols denote **volume down**, **+** denotes **volume up**, toggle-click within one second to trigger

### Full mode
More pop-up windows, some software will pause after the pop-up windows.
- Shortcut + -
- See button description for function
- Download Video
    - *A system mute alert box will pop up every time the download is completed.
    1. video file
        1. online video address, need to make sure the link points to an accessible video
        2. If the file is corrupted or unplayable or unsupported, no change will occur.
    2. streaming media (not supported yet)

### Convenient mode
Minimize pop-ups to prevent interrupting the current program's running state  
- Shortcut - + triggers **Select Video**.
- If the **Download Video** function is set, this shortcut key is changed to trigger **Download Video**.
- Continue to use **Select Video** when the connection of **Download Video** is set to null
    - A silent mode popup window will appear when the download is complete
    - If the remote file is not available then disable the replacement

# Frequently Asked Questions

## Q: How do I select the video resolution?
A: After using the camera + -, detailed information will appear. When the width is greater than the height, it means the video direction is rotated, in most cases the rear camera needs to be 90 degrees counterclockwise and the front camera 90 degrees clockwise, sometimes it needs to be rotated and flipped horizontally. Sometimes it needs to rotate and flip horizontally. The specific direction of the video needs to be observed by yourself due to the different ways of processing by different software. Replace the preview always keep
If the width and height of the video is not consistent with the prompt, the screen may be shifted from the recognized result, the preview will be stretched or even flashback.
- In short, the width and height of the replacement video must be the same as the W, H of the + - shortcut key, and the angle of the replacement video should be adjusted according to the previewed image.

## Q: Is the image rotated after taking a picture?
A: The preview is always in the right direction, some software will process landscape image directly, but rotate the preview when giving it to the user.
- Simply put, according to the direction of the rotated video, rotate the replacement video to the opposite direction once in advance.

# TODO
- Audio Support
- Fix video loops not working in some apps
