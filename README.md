# Usefull things to combine R and python

Follow thin [link](https://www.linkedin.com/pulse/interfacing-r-from-python-3-jupyter-notebook-jared-stufft/) for a brief overview.   

Start by installing the R kernel in the jupyter lab. Follow [this](https://richpauloo.github.io/2018-05-16-Installing-the-R-kernel-in-Jupyter-Lab/) instrcutions (you have to install Anaconda if you do not have it).  

- Install [R](https://cloud.r-project.org/).  
- cd to R.exe    
- Open Anaconda prompt (activate your environment python3).  
  - cd to R. exe
  - Open R by typing: R.exe  
 
 
```
install.packages("devtools")

devtools::install_github("IRkernel/IRkernel")

IRkernel::installspec()
```

If the second command line does not work, you need to install Git [here](https://git-scm.com/download/win).  

Now you can start intefacing jupyter and R.

```
conda activate python3
jupyter notebook
```

