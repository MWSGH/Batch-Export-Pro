# Export Name  
  
## Export Operations  
These operators facilitate the export process and provide feedback on the export status:  
  
**Mesh Export Operator**  
- Exports selected meshes to a specified folder.  
- By default creates 'Mesh' folder in directory of .blend file.  
- Allows setting of custom export directory.  
- Provides feedback on the export status.  
  
**Bake Export Operator**  
- Exports selected meshes to a specified folder for baking.  
- By default creates 'BakeMesh' folder in directory of .blend file.  
- Allows setting of custom export directory.  
- Provides feedback on the export status.  

## Export Groups  
  
Export Groups panel was created to ensure consistency and correctness in the export name management process.  
Populating of the list is handled automatically when new Export Name is introduced.  
It is written to handle updates efficiently with minimal user interface.  
  
**Update Export Name List**  
- Triggered when the export name property is updated.  
- Maintains the list of export names.  
- Ensures no redundant updates occur.  
- Updates the export name mapping when objects are added or removed.  
  
**Unique Entries**  
- Creates a mapping of export names to their corresponding objects.  
- Shows number of associated Objects with specific Export Group.  
- Ensures each Export Group is unique and correctly associated.  
- Automatically updates the group casing to the last entry.  
  
## Export Name UI Elements  
  
The user interface elements provide a clear and interactive way to manage export names and perform related actions. The following elements are displayed to the user:  
  
- **Export Name Box**  
  - Allows users to enter a new export name.  
    
- **Export Groups Section**  
  - Displays the list of export names.  
  - Shows the count of objects associated with each export name.  
    
- **Buttons for Managing Export Name List**  
  - **Refresh List Button**  
    - Refreshes the export name list.  
    
  - **Select Group Button**  
    - Selects the objects associated with the highlighted export group.  
    
  - **Deselect Group Button**  
    - Deselects the objects associated with the highlighted export group.  
    
  - **Remove Group Button**  
    - Removes the export name association for the highlighted export group.  
    
  - **Rename Group Button**  
    - Renames the highlighted export group.  
    
  - **Assign Group Button**  
    - Assigns the export name of the highlighted export group to the selected objects.  
  
  
## Export Name Functions  
  
These functions allow users to manually manage export names, ensuring objects are correctly named and grouped for export:  
  
**Refresh Export List**  
- Clears the current export list.  
- Repopulates it with the updated export name to objects mapping.  
  
**Select Export Group**  
- Selects the objects associated with the highlighted export group in the export name list.  
  
**Deselect Export Group**  
- Deselects the objects associated with the highlighted export group in the export name list.  
  
**Remove Export Group**  
- Resets the export name property for objects in the highlighted export group.  
- Effectively removes the export name association.  
  
**Rename Export Group**  
- Changes the export name for all objects associated with the highlighted export group to a new specified name.  
  
**Assign Export Group**  
- Assigns the export name of the highlighted export group to the selected objects.  
  
