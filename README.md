# REFRESH DESIGN    CES - Python Files Relations

## Idea Description

Our plugin determines the connection between python files basen on imported libraries. One connection suggests that 2 python files start from the same sub functionality and it gives us a overview of all of python files.

## Plugin Description

Python Files Relations plugin generates result.json file which contains 2 lists, of nodes and of links. Nodes represent the python files from chosen project to be analyzed and one link is established between 2 python files sharing the same library or other python package. 

## Installation

### Clone or download this repository:
   git command
### Run the following command:
   docker command  
### For graph view in DX Platform tool, you have to follow the steps:
   1. Download DX Platform and put .dxplatform in /Users/...
   2. Move startDx.bat in other location
   3. Run startDx.bat and open localhost:6060... on your web browser
   4. Run the plugin for result.json file and ces-python-relations...SNAPSHOT.jar to be generated
   5. Create a directory in .dxplatform/plugins named for example pythonRelations
   6. Copy in pythonRelations the 2 files mentioned above, at step 4
   7. In DX Platform, at Plugins section(Configure project), your new plugin will appear
   8. Write commands
   9. See graph results an Relations section(Explore project)
   
## License
MIT / Apache 2.0


