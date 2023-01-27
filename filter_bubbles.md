# Steps for code

This instruction is written from a person that uses: 

 - OSX (MacBook Air 2017)
 - Visual Studio Code
 - Anaconda 2.1.4

N.B. Anancoda 2.1.x is a requirement for this project. Make sure to install it and use Conda for installing other requirements. 

## Environment

First of all, downgrade Python to 3.7.x version, it is necessary in order to install other frameworks. 
### Install pytorch 
Current version is pytorch 1.13 but pytorch 1.4.0 is required
For this project install the stable version of 1.4.0 with CUDA support

```
#Command for Windows
conda install pytorch==1.4.0 torchvision==0.5.0 cudatoolkit=10.1 -c pytorch
```
### Install Scipy 
```
conda install scipy
```
### Install Pandas
```
conda install pandas
```


## Change file path for data
Identify the following block in the main.py 
```python
parser.add_argument("--data_path", type=str, default="/storage/wjwang/filter_bubbles/data/", help="load data path")
```
Change the default path by changing the default parameter with the following path  
```python
./../../data/
```

##Install OpenPyxl

pip install openpyxl



