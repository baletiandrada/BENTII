# CES - Python Files Relations

Python Files Relations is a plugin which determines the connection between python files basen on imported libraries. One connection suggests that 2 python files start from the same sub functionality and it gives us an overview of all python files.


## Motivation

Our plugin generates one file, result.json, which contains 2 lists: with nodes and links. Nodes represent the python files from chosen project to be analyzed and one link is established between 2 python files sharing the same library or other python package. 



## Screenshots

Results from Dx Platform............



## Framework used

We developed this project in **Kotlin** using _IntelliJ Idea IDE_.



## Installation

Please download our **latest release**.

#### Running in docker container:
Run the following command:

```bash
docker run image_name -v a:b -v c:d
```
You must change the path_to_project param to your local path to the project you want to analyze

#### Running in Dx Platform:
1. create dir in ./dxplatform/plugins
2. copy 2 files: plugin-info.json, xxx.jar in the directory mention above
3. In Dx Platform in (Configure project -> Plugins) the plugin will appear and you may create a command. For 'Root folder' configuration field you must enter the path to the project to be analyzed.



## Contributions
We are not open to contributions.
   
   
   
## License
[MIT](https://choosealicense.com/licenses/mit/)


