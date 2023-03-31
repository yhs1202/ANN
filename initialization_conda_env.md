# Conda Cheetsheet

1. Create new env

    ```conda create -n {envname}```

2. Check existing envs

    ```conda info --envs```

3. Activate env

    ```conda activate {envname}```

4. Deactivate env

    ```conda deactivate```

5. Delete env

    ```conda remove --name {envname} --all```

6. Install & Update new packages

    ```conda install {package_name}```

    ```conda update {package_name} --all```



### Reference

https://muten.tistory.com/14
https://github.com/conda-forge/miniforge
https://developer.apple.com/metal/tensorflow-plugin/
------------------------------------------------------------

https://developer.apple.com/forums/thread/721619
https://developer.apple.com/forums/thread/702851

------------------------------------------------------------

Overall steps to install Tensorflow for Apple Silicon

https://www.youtube.com/watch?v=o4-bI_iZKPA&ab_channel=JeffHeaton

https://github.com/jeffheaton/t81_558_deep_learning/blob/master/install/tensorflow-install-mac-metal-jan-2023.ipynb

Installing Miniconda

https://docs.conda.io/en/latest/miniconda.html

or Using Homebrew

    brew install --cask miniconda

How to find Python Interpreter path to set Kernal

    where python

https://docs.anaconda.com/anaconda/user-guide/tasks/integration/python-path/
