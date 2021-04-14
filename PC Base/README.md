# Download the Repository
### if you know git
    git clone https://github.com/KevinTsaiCodes/Novel-Coronavirus-Pneumonia-Face-Mask-Detector-Workshop.git
### or click download zip and extract the zip file
![Screenshot 2021-03-31 093853](https://user-images.githubusercontent.com/53148219/113078065-fb629b00-9204-11eb-8c2a-98f25a05f5ac.png)

# Virtual Environment Setup and Downloading Anaconda
### Download  [Anaconda](https://www.anaconda.com/products/individual)
### Create venv
### Open Anaconda Prompt/ Anaconda Powershell Prompt (Windows)
    conda create --name (venv-name) python=edition
### Open Terminal (Ubuntu Linux)
    conda create --name (venv-name) python=edition
### Example of creating virtual environment (venv)
    conda create --name deeplearning python=3.7
### Activate virtual environment
    conda activate (venv-name)
### Deactivate virtual environment
    conda deactivate (venv-name)
# Package Installation
### Open Anaconda Prompt/ Anaconda Powershell Prompt/ Terminal
### Activate virtual environment
    conda activate (venv-name)
### Go to the directory
    cd [path]/Novel-Coronavirus-Pneumonia-Face-Mask-Detector-Workshop/PC Base
### Install the requirements
### If you have GPU on your PC
    cd On GPU/
#### python 3
    pip3 install -r requirements.txt
#### python 2    
    pip install -r requirements.txt
### If you don't have GPU on your PC
    cd On CPU/
#### python 3
    pip3 install -r requirements.txt
#### python 2    
    pip install -r requirements.txt
### End of installation
   Now, you have installed all the required packages of this repository. All you need to do is execute the program of this repository.
### Run the program
   Remember to change the path to 
    
    [path]/Novel-Coronavirus-Pneumonia-Face-Mask-Detector-Workshop/PC Base
#### python 3
    python3 detect.py
#### python 2
    python detect.py
