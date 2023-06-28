## Blender Motion Capture
> Using 3D modeling methods, an augmented reality application was created that can precisely record and analyze a person's facial
expressions and movements in real time. The AR program records video of a person's face using a computer webcam, analyses the video, and projects the person's facial
expressions and movements onto a 3D model.
### Follow The steps:
1. Basic Settings:
   - The first step is to launch Blender as a super admin.
   - Starting Blender with elevated permissions
   - > For Windows
       - Right-click the blender application and choose: "Run as administrator"
    - > For Mac
      - Start Blender as admin by using the terminal:
      - Navigate to Blender: cd /Applications/Blender/Contents/MacOS
      - Run Blender as admin: sudo ./Blender
    - > For Linux
       - Start Blender as admin using the terminal:
       - Navigate to Blender: cd /user/bin
       - Run Blender as admin: sudo ./blender
       - The admin password must be entered to launch Blender as an administrator using sudo in the terminal. You can launch Blender with just./Blender once the add-on packages have been installed and the terminal has been permitted to access your camera.
2. Then follow these steps:
     1. Download the BlenderARMoCap plugin:
        https://drive.google.com/file/d/1kIYcKjo0DkvaJMTmwg3pItkQThoYMdXG/view?usp=sharing
    2. Open Blender and go to edit->preferences->add on-> install
    3. Locate the downloaded BlenderARMoCap zip file and add it.
    4. Select/check BlenderARMoCap and install dependencies
    5. Select the target pose you need and click start detection
    6. Do it for as many pose as you need and then go to preferences again and add the Rigging module.
    7. Then in your design area, add Armature->Human meta rig and in its properties, select the green color pose icon and click Generate rig
    8. Finally in the blender ar tool, select the driver which contains recently recorded pose from your camera and select rig in the armature, and then click on transfer animation.
    9. This will transfer your pose to the rig you created and will capture the motion as you record in your camera.
