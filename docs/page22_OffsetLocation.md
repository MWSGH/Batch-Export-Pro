# Offset Location

## Overview
This module was created to simplify the process of baking textures in external softwares.  
The Offset Location if enabled is added to Object location while exporting.  
It allows to maintain proper location to preview your models on scene while having them separated for baking in external software.  

## User Interface  
  
### Offset Location Manager Panel  
The Offset Location Manager panel provides a convenient way to manage the Offset Location property of objects. The panel includes options to pick and reset the Offset Location, as well as to display the current Offset Location coordinates.  
  
**Panel Features**:  
- **Offset Location Checkbox**: Can also be found in Settings. Decides if module should be used when Exporting.  
- **Offset Location Label**: Displays the label for the Offset Location.  
- **Offset Location Fields**: Shows the X, Y, and Z coordinates of the Offset Location when an active object is selected.  
- **Pick Location Button**: Copies the active object's location to the Offset Location property.
    - Appearance: Eyedropper (Pipette) icon  
- **Reset Location Button**: Resets the Offset Location to the origin (0.0, 0.0, 0.0).
    - Appearance: X (Delete/Remove) icon  
- **Assign to Selected Button**: Assigns the current Offset Location to the selected Objects.
    - Appearance: Button with text label  

  
## Usage Tips  
- Ensure an object is selected in the scene before using the Pick Location or Reset Location operators.  
- Use the Offset Location panel to quickly access and manage Offset Location properties.  

### Pick Location  
**Appearance:** Eyedropper (pipette) icon button.  
**Description**: Sets the Offset Location of an object based on the active object's current location.  
**Usage**:  
1. Select an object in the scene.  
2. Run the `Pick Location` operator to copy the active object's location to the Offset Location property.  
  
### Reset Location  
**Visual:** X icon button.  
**Description**: Resets value of the Offset Location of an object to (0, 0, 0).  
**Usage**:  
1. Select an object in the scene.  
2. Run the `Reset Location` operator to reset the Offset Location to (0.0, 0.0, 0.0).  
