
# Build Your Own Autonomous Robot, Shaastra 2022
##  CoppeliaSim 4.2.0-Installation

![Image](https://www.coppeliarobotics.com/images/a.jpg)
 
For this module, we'll be using CoppeliaSim. Follow these instructions to install them in your respective OS:

### What is CoppeliaSim
- The robot simulator CoppeliaSim is based on a distributed control architecture: each object/model can be individually controlled via an embedded script, a plugin, a ROS or BlueZero node, a remote API client, or a custom solution. This makes CoppeliaSim very versatile and ideal for multi-robot applications. Controllers can be written in C/C++, Python, Java, Lua, Matlab or Octave.

- CoppeliaSim is used for fast algorithm development, factory automation simulations, fast prototyping and verification, robotics related education, remote monitoring, safety double-checking, as digital twin, and much more. You can find a features of CoppeliaSim [Over Here](https://www.coppeliarobotics.com/features).

- It can be used as a stand-alone application or can easily be embedded into a main client application: its small footprint and elaborate API makes CoppeliaSim an ideal candidate to embed into higher-level applications.
- To get some glimpses you can also watch the [videos](https://coppeliarobotics.com/videos).

### For Windows Users 
- Download CoppeliaSim Edu 4.2.0 for **Windows 64-bit OS** from [here](https://www.coppeliarobotics.com/files/CoppeliaSim_Edu_V4_2_0_Setup.exe) (file size - 155MB).

- Navigate to the downloaded .exefile and double-click it to install the software.

- Once the installation is complete, a shortcut icon to launch the software would have been created on your Desktop. Double-click to launch it. CoppeliaSim will open as shown in Figure-7 with the default scene loaded.

![Image 2](https://raw.githubusercontent.com/kalindkaria/typora-md-assets/master/maze_bot/assets/task_0/sw_install/windows/13_CoppeliaSim_first_launch.png)
**Note** : Incase if Windows defender is not allowing CoppeliaSim_Edu_V4_2_0_Setup.exe to run then download the [binary files](https://www.coppeliarobotics.com/files/CoppeliaSim_Edu_V4_2_0_Win.zip) 

### For Ubuntu Users

- Download CoppeliaSim Edu 4.2.0 for **Ubuntu 18.04 64-bit OS** from [here](https://www.coppeliarobotics.com/files/CoppeliaSim_Edu_V4_2_0_Ubuntu18_04.tar.xz) (file size - 148MB). It will download as .tar.xz (compressed zip) file.

- Download CoppeliaSim for **Ubuntu 16.04 64-bit OS**, click here 1 (file size - 145MB).

Open Terminal and navigate to the directory where this file was downloaded. Run the following command:

```
tar -xf CoppeliaSim_Edu_V4_2_0_Ubuntu18_04.tar.xz
```

This command will decompress and extract the CoppeliaSim software to the folder named CoppeliaSim_Edu_V4_2_0_Ubuntu18_04 in the same directory.

Now type the below commands in sequence to launch CoppeliaSim.

```cd CoppeliaSim_Edu_V4_2_0_Ubuntu18_04./coppeliaSim.sh```

- Now you will be able see the window as shown in the image above

### For macOS Users

- Download CoppeliaSim Edu 4.2.0 for **macOS** from [here](https://www.coppeliarobotics.com/files/CoppeliaSim_Edu_V4_2_0_macOS10_15.zip)
- Unzip the downloaded file and move the unzipped file to Applications as shown in figure below :
![Image 3](https://raw.githubusercontent.com/saurabhcosmos/milkyway/main/images/cop1.png) ![image](https://raw.githubusercontent.com/saurabhcosmos/milkyway/main/images/cop2.png)
![Image 4](https://raw.githubusercontent.com/saurabhcosmos/milkyway/main/images/cop4.png)
- Now open terminal and run following commands:

```
cd /Applications/coppeliaSim.app
sudo xattr -r -d com.apple.quarantine * 
```
<hr>

## Optional Softwares

In the second Session, we'll be using MATLAB to visualise SLAM in our bot using the data from Lidar Sensor in CoppeliaSim. It is going to be a demo and participants can subscribe for Educational Version of MATLAB. For more details visit: [MATLAB for Students](https://in.mathworks.com/products/matlab/student.html). Note that it is completely optional to have MATLAB for the session.

After installation of MATLAB, you have to install *Navigation Toolbox* from Add-Ons tab. 
