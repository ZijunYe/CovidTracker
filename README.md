# CovidTracker

Build in Python, Beautiful Soup4, tkinter

## ScreenShot Result
![image](result.png)



## How to install pip & create virtual environment? 
   - you have two way to do 
      1. using pyCharm --> it automatic install virtual environment and pip for you 
      2. install by self in terminal; here is steps: 
      ```cd <folder-with-my-project> ```  # Put here the folder name 
      
       ```mkdir main.py```          # Create a dedicated app directory.
       
       ```cd corona-app```              
      
      ```sudo easy_install pip``` #install pip 
      
      ```python3 -m pip install virtualenv``` #install virtualenv 
      
       ```virtualenv venv```            # Create the virtual environment 'venv'
       
       ```source venv/bin/activate``` #activate environment
       
       ```pip install requests 
          pip install beautifulsoup4```  
          #two  module use in our project
      

      
## What problem faced in this project?
I struggled for an hour to solve the problem "Python ModuleNotFoundError: No module named 'requests'"
In multiple article and video shows that there two reasons causing this kind problem.   
1. uninstall ``` pip install requests ```
2. program can't find path 

How do I solved? I believe my problem is causing by reason2. I changed python project in PsCharm and check out "Inheritat gloabl site-packages" then everything works. 
![image](Solution.png)











