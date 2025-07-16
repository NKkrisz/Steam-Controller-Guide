# 3D Printing Parts For The Steam Controller

## CAD Files / Models
- [Official CAD Release](https://store.steampowered.com/news/app/353370/view/3931035846865618326)
- [Additional 3rd Party Models - Includes Missing Ones From The Official Release](https://github.com/MichaelZaugg/OpenSteamController-Continued/tree/master/Mods/CAD-Releases)

## Potential Issues & Solutions

### File size too large
1. [Download Blender (Available On Steam too)](https://www.blender.org/download/)

2. Select and delete default cube
    - ![Default Cube](../Images/3D_Printing_Parts/Default_Cube.png)

3. Import model (File > Import > File Type > File Browser)
    - ![Importing](../Images/3D_Printing_Parts/Importing.png)
    - ![File Browser](../Images/3D_Printing_Parts/File_Browser.png)

4. Add decimate modifier (Blue Wrench > Add Modifier > Search > Decimate)
    - ![Add Modifier](../Images/3D_Printing_Parts/Add_Modifier.png)
    - ![Selecting Decimate](../Images/3D_Printing_Parts/Selecting_Decimate.png)
    - ![Decimate Settings](../Images/3D_Printing_Parts/Decimate_Settings.png)

5. Decrease ```Ratio``` value until acceptable quality loss / file size requirement (```Face Count``` should go down)
    - ![Decimated](../Images/3D_Printing_Parts/Decimated.png)

6. Select and export model (File > Export > File Type > File Browser)
    - ![Exporting](../Images/3D_Printing_Parts/Exporting.png)

7. The file size should be smaller
    - Before
        - ![Before (311.0 MiB)](../Images/3D_Printing_Parts/Model_Before.png)
    - After
        - ![After (31.1 MiB)](../Images/3D_Printing_Parts/Model_After.png)

### Slicer Issues
- Use [Blender](https://www.blender.org/), [FreeCAD](https://www.freecad.org/) or other alternatives to fix the errors pointed out in the models (hidden holes, structural flaws etc...)

### Preventing Parts From Breaking / Being Fragile
- Use a tougher material
- Increase rigidity by editing the models
    - Try making certain areas thicker

#### Additional Notes
- CAD users should use .step files for making changes