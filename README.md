# Usefull things to combine R and python

Follow thin [link](https://www.linkedin.com/pulse/interfacing-r-from-python-3-jupyter-notebook-jared-stufft/) for a brief overview.   

Start by installing the R kernel in the jupyter lab. Follow [this](https://richpauloo.github.io/2018-05-16-Installing-the-R-kernel-in-Jupyter-Lab/) instrcutions (you have to install Anaconda if you do not have it).  

- Install [R](https://cloud.r-project.org/).  
- cd to R.exe    
- Open Anaconda prompt.  
  - cd to R. exe
  - Open R by typing: R.exe  
 
 
```
install.packages("devtools")

devtools::install_github("IRkernel/IRkernel")

IRkernel::installspec()
```
