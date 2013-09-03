Ragnarok - Maya to UDK Level Exporter
Version 1.0.130612
 
===========================================================================================
[Version 1.0]
+ Added Tools and Help menu
+ Ragnarok components can be updated directly from exporter, no need for additional script
+ You can change your object rotation to XZY directly from exporter
+ Shortcut for object export is now inside Tools menu
+ Minor GUI improvments and changes

--------------------------------------------------------------------------------------------
[Version 0.9]
+ Script will not crash export process if there is no Raganrok component on the mesh. Instead it will print errors found after export process has completed
+ Fixed error that emerges when attempting to save to same destination after "Ragnarok Tag not found on object" error upon previous export
+ Made available object exclusion from export procedure
+ GUI improvements
IMPORTANT!!!
New functionality has been implmented (object exclusion from export procedure), so to use Ragnarok 0.9 and future versions all meshes in scene that have implemented Ragnarok system need to update. You can manually delete ragnarok component and add new but I suggest that you use this little script. It will iterate through your selection and look for required objects to update.

--------------------------------------------------------------------------------------------
[Version 0.8]
+ Added helper script to upadte objects so that they can be used with newest version. NOTE: This will be inside GUI in final version.
+ Added function to launch Export dialog directly from Ragnarok
+ Added Map input field to specify name of your map. This bug caused UDK to launch Save As dialog instead of saving map as it normally should.
+ GUI improvements 
+ Minor bug fixes
+ Minor GUI changes

--------------------------------------------------------------------------------------------
[Version 0.7]
+ Do your level design in Maya
+ One click export from Maya, one click import in UDK
+ None of the basic principles of game design are broken, working fine with mesh instances
+ Intuitive UI
+ Easy to use
+ There was big issue with rotations. It's fixed now. Make sure that you are working with XZY Rotate Order on your models in Maya and that Up axis: Y (Preferences > Settings) in your scene. It should all work fine now.
+ Also, minor code adjustments have been made. ;)

=============================================================================================
