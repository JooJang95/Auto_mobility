## Common Hardware Development Environments
● scout MINI 
<img src = "https://user-images.githubusercontent.com/114387340/212227001-c9e5743f-663a-44a2-89ca-7f697f1a2e16.png" width="20%" height="20%">

● Intel L515 RealSense 
<img src = "https://user-images.githubusercontent.com/114387340/212227063-12a3fd86-1d66-45c5-8b28-5a5579318212.jpg" width="20%" height="20%">

● Intel L515 NUC
<img src = "https://user-images.githubusercontent.com/114387340/212226928-40af66cb-0e9d-4350-b518-d6656900e9b1.png" width="20%" height="20%">

## Common Software Development Environments
Ubuntu 18.04 Installation

1. ROS Installation
2. Reference Site 
<<https://wiki.ros.org/melodic/Installation/Ubuntu>> 1.2 ~ 1.6.1 Installation

3. scout_mini SDK Installation
Reference Site 
<<https://github.com/agilexrobotics/ugv_sdk>>

4. scout_mini Package installation
Reference Site
<<https://github.com/agilexrobotics/scout_ros>>

5. intel Realsense L515 SDK installation 
     **Ubuntu 18.04**
         
         $ sudo add-apt-repository "deb http://librealsense.intel.com/Debian/apt-repo bionic main" -u
         $ sudo apt-get install librealsense2-dkms
         $ sudo apt-get install librealsense2-utils
         $ sudo apt-get install librealsense2-dev
         $ sudo apt-get install librealsense2-dbg
         
         ## test
         $ realsense-viewer
         

## Project. ladar

**library used**

        1. install pyzbar
        2. install pyrealsense2
        3. install numpy
        4. install cv2
        5. install time
        
● ** Mapping with the Scout Mini **

            # Parts Used #
            ● Scout mini : 1
            ● Intel NUC : 1
            ● Intel L515 3D Rider sensor : 1
            
<img src = "https://user-images.githubusercontent.com/98440628/176838379-9cd06580-97e5-4a1a-914f-cd0a0eb70aae.jpg" width="30%" height="30%">
            
● **Video with QR code Recognition**





● **Modified scout MINI for SLAM recognition**

 ● **Video of my office that Use SSL_SLAM // Reference Site <<https://github.com/wh200720041/ssl_slam>>** 
