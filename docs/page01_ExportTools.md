# Export Tools  
  
These operators facilitate the export process and provide feedback on the export status:  

  
### Mesh Export Operator
- Exports selected meshes to a specified folder.  
- By default creates 'Mesh' folder in directory of .blend file.  
- Allows setting of custom export directory.  
- Provides feedback on the export status.  
  
  
### Bake Export Operator  
- Exports selected meshes to a specified folder for baking.  
- By default creates 'BakeMesh' folder in directory of .blend file.  
- Allows setting of custom export directory.  
- Provides feedback on the export status.  

<br>
<br>
<br>
  
## Export Directories
***Please make sure you have permission to create folders and files in the Directory you choose.***  
If .blend file is saved in a folder 'files' then the 'Mesh' and 'BakeMesh' folders will be created as 'files' folder siblings. 
Add-on automatically detects if the folders already exists and if they do not exist yet it creates it.

**Folder structure with default settings will look in one of two ways (depending if your .blend file is in "Files" folder):**  
  ...\YourFile.blend  
  ...\Mesh\MeshExport_1.fbx  
  ...\BakeMesh\BakeExport_1.fbx  
or  
  ...\Files\YourFile.blend  
  ...\Mesh\MeshExport_1.fbx  
  ...\BakeMesh\BakeExport_1.fbx  
  
**You can set custom directories inside of Settings box.**