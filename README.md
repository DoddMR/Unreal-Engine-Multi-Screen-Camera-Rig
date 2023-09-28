# Unreal-Engine-Multi-Screen-Camera-Rig
<h3>Description</h3> 
<p>
  This UE plugin allows an UE application to work across 3 screens<br>
  It works by using 3 Scene Capture Component 2D which streams to a unique render target<br>
  Each render Target is then applied to a material which is then applied on to a plane static mesh<br>
  The main camera is positioned to look at the 3 panels and streams at 5760*1080<br>
</p>
<h3>How to install and use</h3>

<p>
  Download and Unzip the MRCameraRigPlugin <br>
  Move the file into the Plugins folder of your UE applciation <br>
  If this folder doesnt exist create a new folder called "Plugins" and then move the downloaded into the newly create file <br>
  Open your UE application and go to Plugins - MRCameraRigPlugin C++ Classes - MRCameraRigPlugin and Public in the content drawer<br>
  Drad and drop MRCameraRig into your environment and posses the pawn<br>
</p>
<h3>UE Environment Changes</h3> 
<P>
  Go to engine - Rendering - Shadows and change Shadow map methods to "Shadow maps"<br><br>
  Go to engine - Rendering - Default Settings and change Anti-Aliasing method to "Fast Approximate Anti-Aliasing (FXAA)"<br><br>
  Create a post processing volume<br>
  Change Infinite Extent(Unbound) to True<br>
  Change Min EV100 and Max EV100 to 1.0<br>
  Change Amount and Max in Motion Blur to 0.0<br><br>
  Update the axis mappings to reflect this screenshot<br>
  ![AxisMappingScreenshot](https://github.com/DoddMR/Unreal-Engine-Multi-Screen-Camera-Rig/assets/144355506/6c4e6340-d265-4547-9b8c-5796a50afbc1)


</P>
