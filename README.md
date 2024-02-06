# AR-Face-Tracking-Filter-App-in-Unity
Developed my first face tracking filter application for android phones using unity. It detects and tracks the face to display custom digital content on it.

# Steps to add custom video
# Step-0:
  a) Make sure to have all the pre-requisites such as android SDK & NDK installed in unity.
  b) Download the repository as zip file or paste the git-url in the package manager inside unity.
  
# Step-1:
  a) Download the video of your choice.
  b) Paste it in the assets folder inside unity.
  c) Single click on the video and make the following changes to remove the time stamp error if it comes in the console window:
      a. Look in the inspector window after single-clicking on the video file.
      b. Inside the sRGB(color texture) tab, after pressing on the android version, change the codec to VP8 and apply the changes.
  d) Click on the VideoPlayer object in the hierarchy window.
  e) Drag and drop the video from assets to the Video-clip section inside the Videoplayer tab inside the inspector window.

# Step-2:
  a) Go to File -> Build setings.
  b) Press on Add open scenes to add the AR Filter scene inside the the scene build hierarchy.
  c) Finally Build/Build and run.
