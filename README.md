# Talky-Walky-Avatar

This Project contains the actual 3D Model of the Talky Walky Avatar in the form of a blender file.

After the initial creation through [Meshy](https://www.meshy.ai/discover), Talky Walky was adjusted and partially modelled from scratch in blender. Therefore this file also contains all of the manually created blendshapes and animations.

In order to open the walky_talky.blend file, blender needs to be installed first. It can be downloaded for free from the official [blender website](https://www.blender.org/download/).

# Mesh

In order to change the mesh/shape of the model, go to the tabs 'Modeling' or 'Scultping', depending on your prefered method.

# Blendshapes

The Blendshapes can be found for several components:

- Head: Contains all of the blendshapes which are needed to make the robot talk, namely A, B, C, D, E, F and X. Then there are also some additional blendshapes which can be used in combination with others to show certain emotions.
- Left Eye: Contains blendshapes for different emotions, such as happy, sad or star (turns the eyes into stars, just like the star emoji 🤩, to express excitement or amazement)
- Right Eye: The same as the right eye, but the blendshapes are mirrored.
- Left Eyebrow: Contains two different positions of the eyebrows, one to express sadness and another one to convey surprise.
- Right Eyebrow: Same as the left eyebrow, but mirrored.

They can be accessed in the Data tab of any of the objects named above in the category 'Shapekeys' (another word for blendshapes). By changing the Value of each shapekey (ranging 0 and 1), the intensity of the deformation can be controlled.

This can be seen in the image below.

![image showing blend shapes](/Assets/blendshapes.png)

# Animations

Animations can be found in the Animation tab on top when choosing 'Action Editor' for the window below the character. There are two manually made animations available in the file, wave_animation and idle_animation. 

Check out the image below for a visual representation of the described scene.

![image showing animations](/Assets/animation.png)

# Export

If the model gets modified and meant to be used in any of the provided lipsync projects, it has to be re-exported as a .glb file. Preferably with the same name as the old file, otherwise the code has to be adjusted. 