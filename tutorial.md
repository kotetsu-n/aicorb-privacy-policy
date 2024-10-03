# Installation

## Extract the zip file and place the contents as follows:
1. C:\Users\{$USERNAME}\AppData\Roaming\Autodesk\Revit\Addins\{$YOURREVITVERSION}\AiCorb.addin
2. C:\Users\{$USERNAME}\AppData\Roaming\Autodesk\Revit\Addins\{$YOURREVITVERSION}\AiCorb\AiCorb.dll
3. C:\Users\{$USERNAME}\AppData\Roaming\Autodesk\Revit\Addins\{$YOURREVITVERSION}\AiCorb\MaterialDesignColors.dll
4. C:\Users\{$USERNAME}\AppData\Roaming\Autodesk\Revit\Addins\{$YOURREVITVERSION}\AiCorb\MaterialDesignThemes.Wpf.dll
5. C:\Users\{$USERNAME}\AppData\Roaming\Autodesk\Revit\Addins\{$YOURREVITVERSION}\AiCorb\Newtonsoft.Json.dll

# Uninstallation

## Delete all the files placed during installation.
The past recognition result data displayed in the design palette is saved at the following location. Delete it if necessary:
- C:\Users\{$USERNAME}\AppData\Local\AiCorb\

# How to use
## You can use this plugin by following the steps below:
1. Create a new Conceptual Mass family.
2. After creating the volume to which you want to apply the facade, run "FacadeByImage" in the AiCorb tab.
3. Agree to Load Families the first time.
4. Open the image loading window by selecting "Create New" from the design palette.
5. Select the image you want to load by clicking "Load Image."
6. Move the vertices of the rectangle displayed in red to specify the area you want to load.
7. Press "Crop" to finalize the area, or "Reset" to redo the selection.
8. If needed, enter a desired name in the "Name" field.
9. Press "OK" to execute the design loading.
10. Select the loaded result registered at the bottom of the design palette.
11. Press "Select Face" and select the surface of the volume you want to apply it to.
12. Press "Apply" to apply the recognition result.

## If the parameters of the recognition result are unsatisfactory:
1. Select the recognition result you want to modify.
2. Press "Edit."
3. Manually adjust each parameter from "Edit Parameters."
4. After modifications, press "Update."

## To delete an unwanted recognition result:
1. Select the recognition result you want to delete.
2. Press "Delete."

## To define a new design by manually modifying parameters based on a recognition result:
1. Select the recognition result you want to modify.
2. Press "Duplicate."
3. Enter a name and press "OK."
4. Select the duplicated design and modify the parameters as needed.

## Currently, the ugrid corresponding to the floor height is fixed. However, you can manually modify this. By following the steps below, you can explore more flexible design options:
1. To change the panel size in the floor height direction, modify the U Grid Distance of the Divided Surface.
2. To change the width of the panel size, modify the V Grid Distance of the Divided Surface.
3. Press the "Apply" button to apply the changes.