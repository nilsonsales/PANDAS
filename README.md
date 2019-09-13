# PANDAS
Using Anaconda and PANDAS.  

Adding conda to your PATH using **fish**, add it to your user's profile:
```bash
set -U fish_user_paths ~/bin/anaconda3/bin $fish_user_paths
```

If you want to remove it later, use
```bash
echo $fish_user_paths
set -U -e fish_user_paths[1]
```
Where [1] means the first line  
  
  
### Activating conda's environment
To activate the conda's environment, you use:
```bash
conda activate root
```
The first time you do it, it'll ask you to initialize it for fish (by default):
```bash
conda init fish
```
To prevent conda to activate by default, use:
```bash
conda config --set auto_activate_base false
```

Then it will be activated by default. In order to disable it and use your system's default python, use:
```bash
conda deactivate
```
