# 3rd-ML100Days
For the 3rd-ML100Days

  
# To find your Anaconda Python root directory
1. On your cmd mode to type this "jupyter notebook --generate-config"
2. If you have default file which is jupyter_notebook_config.py then will have a notice to ask you want to over this file.
3. Now you almost get it.

# To change your Anaconda Python web root directory
1. First we use "jupyter notebook --generate-config" to check the file where is it.
2. Open the jupyter_notebook_config.py, to find the tag "notebook_dir" and modifiy the right path.( Should remeber before tag "#" need remove )

# To check the package and function name
On Python you can import by absolute or relative path so sometimes your programe got the ModuleNotFoundError that means the package can't match.
print(type(__name__), __name__) # Programe running name
print(type(__package__), __package__) # Running which package
