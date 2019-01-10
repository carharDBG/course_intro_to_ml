## Handout
### 1. Have a look at the GitHub repository for this course

[https://github.com/ThorstenHen/course_intro_to_ml](https://github.com/ThorstenHen/course_intro_to_ml)

Read the General Information and follow the links to:
- technologies
- ML resources
- Schedule of the course

### 2. Install this GitHub repository on Binder

1. go to [mybinder.org/](https://mybinder.org/)
2. Enter the repository name into the text field: **GitHub repository name or URL**
https://github.com/ThorstenHen/course_intro_to_ml
3. Click on the **launch** button and wait. 
This will get the code from the repository and install all necessary python modules
4. Run the **hello_world.ipynb** example.

### 3. If Binder is NOT working
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

Now you are ready to go for the course!
