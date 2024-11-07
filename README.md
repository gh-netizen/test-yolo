# YOLO testing
This is a project for YOLO testing

## Links
Git:  
https://git-scm.com/downloads/win  
Anaconda3-2021.11-Windows:  
https://repo.anaconda.com/archive/  
CUDA Toolkit 11.2 Downloads:  
https://developer.nvidia.com/cuda-11.2.0-download-archive  
cuDNN Archive:  
https://developer.nvidia.com/rdp/cudnn-archive  
Visual Studio:  
https://visualstudio.microsoft.com/vs/older-downloads/  
Basil leaf identifier:  
https://universe.roboflow.com/basil-detection/basil-leaf-identifier/  
Yolov9:  
https://github.com/WongKinYiu/yolov9  

## Software used
Anaconda3-2021.1.11 with Python 3.9  
Visual Studio Community 2019 16.8.2  
Git 2.45.2.windows.1  

## Other downloads

## Executed outside enviroment
Create enviroment:
```
python -m venv myenv
```

List of enviroments:
```
conda env list
```

Activate enviroment:
```
.\myenv\Scripts\activate 
```

## Executed inside enviroment
Install ipykernel Python package into environment:
```
pip install ipykernel 
```

Install kernel specification pointing to environment:
```
python -m ipykernel install --name=mykernel
```

Verify kernel list:
```
jupyter kernelspec list
```

Activate jupyter lab:
```
jupyter lab
```

## Executed in jupyter notebook
See jupyter notebook.

## Other tips
-Make sure to have all correct and compatible depencies.  
-Make sure to have the yolov9-m.yaml and yolov9-m.pt files, if not download it manually from yolov9 repository.  
-'Basil leaf identifier' datset can be downloaded without a key from the roboflow link.
