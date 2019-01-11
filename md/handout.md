## Handout
### 1. Have a look at the GitHub repository for this course

[https://github.com/ThorstenHen/course_intro_to_ml](https://github.com/ThorstenHen/course_intro_to_ml)

Read the General Information and follow the links to:
- technologies
- ML resources
- Schedule of the course

:star: Give us a star if you like it

### 2. Launch Jupyter Notebooks (pick one of three alternatives)
#### 2.1 Easiest way
1. go to either of:
    - [https://binder.pangeo.io/v2/gh/ThorstenHen/course_intro_to_ml.git/master](https://binder.pangeo.io/v2/gh/ThorstenHen/course_intro_to_ml.git/master)
    - [https://mybinder.org/v2/gh/ThorstenHen/course_intro_to_ml.git/master](https://mybinder.org/v2/gh/ThorstenHen/course_intro_to_ml.git/master)
3. Be patient and wait.

#### 2.2 Install new from GitHub repository on Pangeo or MyBinder
1. go to either of:
    - [binder.pangeo.io/](https://binder.pangeo.io/)
    - [mybinder.org/](https://mybinder.org/)
2. Enter the repository name into the text field: **GitHub repository name or URL**
https://github.com/ThorstenHen/course_intro_to_ml
3. Click on the **launch** button and wait. 
This will get the code from the repository and install all necessary python modules

#### 2.3 If Pangeo and MyBinder are NOT working you can launch jupyter notebooks locally
1. Go to [https://github.com/ThorstenHen/course_intro_to_ml](https://github.com/ThorstenHen/course_intro_to_ml)
2. Click on the green **"Clone or download"** button. 
    * Then **"Download ZIP"**. 
    * Then "Save as". Please put on **"N: drive"** and unzip
3. From AppLauncher launch a console: 11_Development_Applications >> OSS >> Python3 >> Python3
4. In the console type:
~~~~
import os
os.system('M:/WINPROG/Anaconda3/Scripts/jupyter-notebook --NotebookApp.notebook_dir="N:"  --NotebookApp.iopub_data_rate_limit=10000000')
~~~~
5. run notebook in Browser using URL: localhost:8888

### 3. Now you are ready to go for the course!
- Run the **hello_world.ipynb** example.
