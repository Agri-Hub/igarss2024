# IGARSS 2024 Summer School - From Data to Wisdom 


## Installation of the virtual envirnoment
Please follow the steps below:
* Download the workshop.yaml file
* Open the anaconda navigator/terminal
* Run the following commands:
```sh
conda env create -f workshop.yaml
```
Afterwards,
```sh
conda activate datacube
```
* An error may rise related to Microsoft Visual Tools. In order to solve it:
    * Download download Microsoft C++ Build from  Tools:https://visualstudio.microsoft.com/visual-cpp-build-tools/
    * Press Modify during installation and make sure that you have checked the C++ build tools
    * Try running ```pip install hdstats``` from the anaconda navigator
