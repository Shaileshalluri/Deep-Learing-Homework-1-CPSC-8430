# Deep-Learing-Homework-1-CPSC-8430

Shailesh Alluri

The files in this folder and their purpose are listed below. A description of the funtionality of each file can be found at the top of that file: <br />  
Part1-1.ipynb - source code for Part1.1 Simulate a Function (Task 1 of part 1).  <br />
Part1-2.ipynb - source code for Part1.2 Train on an Actual Task(Task 2 of part 1).  <br />
Part2-1.ipynb - source code for Part2.1 Visualize the Optimization Process.  <br />
Part2-2.ipynb - source code for Part2.2 Observe Gradient Norm during Training.  <br />
Part2-3.ipynb - souce code for Part2.3 Calculating minimal ratio at zero gradient.  <br />
Part3-1- Random Labels.ipynb - source code for Part3.1 Can Network fit Random Labels.  <br />
Part3-2-Number of Params.ipynb - source code for Part3.2 Number of Parameters VS.Generalization.  <br />
Part3-3-1 - Interpolation.ipynb - source code for Part3.3.1 Flatness VS. Generalization.  <br />
Part3-3-2-batch sz.ipynb - souce code for Part3.3.2 Flatness VS. Generalization.  <br />
Deep_Learning_HW1.pdf - Assignment report with analysis of code and results.  <br />

To run these files, the following libraries are required: <br />
python 3.8  <br />
Pytorch 1.7  <br />
Tensorflow 2.4  <br />
Matplotlib 3.2.2  <br />
Numpy 1.19  <br />

The dataset required to run the source code is the MNIST dataset from the torchvision datasets library in pytorch. Once the dataset is downloaded to this 
pathfile, it can be used by every other file and is the only file you will need to download. In every file that requires the MNIST dataset, there is a
line of code that grabs the dataset.  <br />
It is provided below: <br />
trainingSet = datasets.MNIST('', train=True, download=False, ...)  <br />
To download the dataset, change the download option to True. This is done for you in the first source code file (Part1_TrainOnActualTask.ipynb). You will need internet connect to download the dataset.

To run the following .ipynb files, open juyper notbooks in an enviornment with
the above packages installed and run the cells in the file from top to bottom. 
