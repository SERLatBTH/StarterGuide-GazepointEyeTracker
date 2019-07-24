# Gazepoint Eye Tracker


## Content
* [Where To Find](#where-to-find)
* [In The Box](#in-the-box)
* [How To Make It Works](#how-to-make-it-works)
  * [Assembly](#assembly)
  * [Charging The Batteries](#charging-the-batteries)
  * [Powering Up](#powering-up)
* [Device's Functionalities and Features](#devices-functionalities-and-features)
* [Safety Guidelines](#safety-guidelines)
  * [Environmental Consideration](#environmental-consideration)
  * [Operation](#operation)
  * [Pre-Flight Checklist](pre-flight-checklist)
* [SDK](#sdk)
* [Accessories](#accessories)
  * [DJI Goggles](https://github.com/SERLatBTH/DJIGoggles)
  * [Mavic 2 Fly More Kit](#mavic-2-fly-more-kit)
  * [Backpack](#backpack)
* [Putting The Device Back](#putting-the-device-back)
* [More Documentations](more-documentations)

## Where to Find
Storage Room - Shelf A1

## In The Box
Below is the pruduct list that the eye tracker contains. Please check the contents when you recieve it and before you return.
1. Box
2. Eye tracker
3. Eye tracker bag
4. Password card
5. Eye tracker holder/Tripod
6. USB power cable
7. USB data cable
![alt text](/images/eyeTracker.jpg)

## How To Make It Works

### Assembly

1. Download and install Gazepoint software on your computer. (https://www.gazept.com/downloads/)

2. Unpack your Gazepoint GP3 device.

3. Attach tripod (or optional VESA or laptop mount) and cables to the GP3.
   * By Tripod
      - Plug in USB power cable and USB data cable to eye tracker and connect to your computer. Recommandation: connect eye tracker directely to computer and avoid USB hub or switch. GP3 HD requirs USB 3.0 data port for 150Hz.
   * By VESA and Laptop Mount
      - Join eye tracker unit to VESA arms (short) with 2 thumbscrews. Each arm part has Top-Left 100mm and Top-Right 100mm stamped on it. For a 100MM VESA mount, make sure Top-Left 100.. is facing up on the left Arm and Top-Left 100mm is facing up on the right Arm. Attach VESA arms with VESA rods (long) using 4 supplied 1/2n 6-32 screws. Position eye tracker under monitor and line up VESA Rods with VESA mount holes on monitor.
      - Hold eye tracker with one hand as close to bottom edge of monitor as possible and attach VESA rods to monitor with 4 thumbscrews. Adjust angle of eye tracker to point towards the eyes (ideal distance is 65cm).
      - For Laptop Mount attach eye tracker to Laptop Mount as illustrated and secure with 2 thumbscrews. Placce on laptop aboce or on function keys. Tilt angle towards eyes as necessary.

4. Position the GP3 to point at your eyes at an upwards angle. Ideally, the unit is 30 cm below eye level and 65 cm away.
   - Position the eye tracker below your screen or on your laptop, centered and as close to the bottom edge of your screen as possible. This is approximately arm's length (-65cm or 25 inches) from the user.
   - The device should be appoximately 40cm or 15 inches below eye level and it should point at an upwards angle towards the eyes.
   Avoid incandescent lighting or sunlight illuminating directly into the eye tracker or onto the user face, The eye tracker will work in low light.
   - If the user is wearing glasses, tilt the eye tracker towards the eyes at a steeper angle to avoid reflections.

5. Plug USB cables into your computer.

### Starting up
6. Start Gazepoint Control to calibrate your unit.
   - In Gazepoint Control, ensure that the camera tracks the eyes correctly as indicated by green boxes around the eyes. The sliding horizontal dot should be green and mostly centered when the distance is optional.
   - If using an external monitor, click on Select Screen to identify the Active Screen for the eye tracker.
   - Click on Calibrate and follow the white target with your eyes as it cycles through the 5 calibration points. Try keeping your head still and avoid blinking during the calibration. Test the calibration by looking at any of the targets on the screen.
   - If calibration accuracy is acceptable, click on the screen or press ESC to accept calibration. If a retry is needed, press C to calibrate again.

7. Start Gazepoint Analysis to begin capturing gaze data.
   - Minimize Gazepoint Control and leave it running and start Gazepoint Analysis. Select new project and define a new folder for your project. A unique folder is required for each project.
   - Choose and specify your media type (text/image/video/web/web aggregate)
   -  Click Start Record to begin experiment.

### How to set up an experiment
1. Prepare your text, image, and video file that will be used in your experiment.

   A text file can be used to give instructions to your text subject at the start of your experiment. A text file is limited to 15 lines of display.

2. Start Gazepoint Control and calibrate your eye tracker.

3. Start Gazepoint Analysis, begin a new project, and choose media type Text. Choose your .txt file and set the display duration.

4. In the Media List box on the left side, click the Add icon to add additional media items, which may be an image file. Choose your .jpg file and set your display duration. Repeat to add media item for the video file.

5. Minimize Control and Analysis windows or move them to your tester screen. We recommend a dual screen setup so that there is one for the test subject and one for the tester to start, stop, and monitor the testing.

6. Press CTRL + ALT + R or click Record to begin your experiment, and start recording. (Test subjects can use the spacebar to advance to the next media item.) Recording will stop after the last media item has been displayed.

7. Click Analyze Data icon.

8. Click Fixationmap icon.

9. Click Play icon to review recording.

10. Click Export icon to export the data. Data is exported to the \result folder inside your project folder.

### How to create a heat map
1. Start Gazepoint Control and calibrate your eye tracker.

2. Start Gazepoint Analysis, begin a new project, and choose media type Screen capture.

3. Minimize Control and Analysis windows.

4. Load your stimulus material, which can include an image, video, PDF, game, webpage, or other testing software.

5. Press CTRL + ALT + R to start recording, and begin your test.

6. Press CTRL + ALT + S to stop recording.

7. Click Analyze Data icon.

8. Click Visualization icon, and a settings window will provide different size and opacity choices.

9. Click Play icon to review recording

### How to create a fixation map
1. Start Gazepoint Control and calibrate your eye tracker.

2. Start Gazepoint Analysis, begin a new project, and choose media type Screen capture.

3. Minimize Control and Analysis windows.

4. Load your stimulus material, which can be an image, video, PDF, game, webpage, or other testing software.

5. Press CTRL + ALT + R to start recording, and begin your test

6. Press CTRL + ALT + S to stop recording.

7. Click the Analyze Data icon and click the Visualization icon to access the Visualization Settings. Choose a fixation map.
8. Click the Play icon to review recording.

9. Click the Export icon to export the data. Data is exported to the \result folder inside your project folder.

   Data Files:

   0001-user.csv – contains all captured data
   
   0001-user-fix.csv – only the fixations are listed
   
   CurrentAOIStatisticsX.csv – lists the statistics for the AOIs (only created if AOIs are used)
   
   CurrentImageX.png – copy of image currently in the Analysis display window (can be paused at any point of recording)

10. Click Export icon to export the data. Data is exported to the \result folder inside your project folder.

### Gazepoint Analysis Hotkeys

CTRL+ALT+R = start data record

CTRL+ALT+S = stop data record

ALT+ left arrow = go to start of recording

ALT+ right arrow = go to end of recording

ALT+ z = toggle playback zoom

ALT+ p = play recording or pause recording

ALT+ up arrow = skip to previous recording

ALT+ down arrow = skip to next recording
