# AR-Face-Tracking-Filter-App-in-Unity
Developed my first face tracking filter application for android phones using unity. It detects and tracks the face to display custom digital content on it.<br>
Use on unity version 2022.3.10f1 and above.

# Steps-to-Add-Custom-Video:
# Step-0:
  a) Make sure to have all the pre-requisites such as android SDK & NDK installed in unity. <br>
  b) Download the repository as zip file or paste the git-url in the package manager inside unity.<br>
  
# Step-1:
  a) Download the video of your choice.<br>
  b) Paste it in the assets folder inside unity.<br>
  c) Single click on the video and make the following changes to remove the time stamp error if it comes in the console window:<br>
      &nbsp; &nbsp;  a. Look in the inspector window after single-clicking on the video file.<br>
      &nbsp; &nbsp;  b. Inside the sRGB(color texture) tab, after pressing on the android version, change the codec to VP8 and apply the changes.<br>
  d) Click on the VideoPlayer object in the hierarchy window.<br>
  e) Drag and drop the video from assets to the Video-clip section inside the Videoplayer tab inside the inspector window.<br>

# Step-2:
  a) Go to File -> Build Settings.<br>
  b) Press on Add open scenes to add the AR Filter scene inside the the scene build hierarchy.<br>
  c) Finally Build/Build and run.<br>
