# Step 5: Install OpenCV on Mac
https://www.learnopencv.com/install-opencv3-on-macos/



```sh
nano ~/.bash_profile

# Virtual Environment Wrapper
VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python2
source /usr/local/bin/virtualenvwrapper.sh

or 

echo "# Virtual Environment Wrapper"
echo "VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python2" >> ~/.bash_profile
echo "source /usr/local/bin/virtualenvwrapper.sh" >> ~/.bash_profile

# 
source ~/.bash_profile
```


```sh
############ For Python 3 ############
# Create virtual environment
mkvirtualenv machine-learning-py3 -p python3
workon machine-learning-py3
  
# Now install python libraries within this virtual environment
pip install numpy scipy matplotlib scikit-image scikit-learn ipython pandas
pip install cython imutils
pip install opencv-python
# List packages installed
pip freeze

# Quit virtual environment
deactivate


```

# Git
```

git remote add origin https://github.com/robin8a/udemy_raspberry_machine_learning.git
git push -u origin master

touch initial

git add initial

git commit -m "initial commit"

git push -u origin master

```