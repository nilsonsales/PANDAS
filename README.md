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
In order to create your own environment, use:

Activating:
```bash
conda activate root
```
The first time you try it, it'll ask you to initialize it for fish:
```bash
conda init fish
```

Then it will be activated by default. In order to disable it and use your system's default python, use:
```bash
conda deactivate
```
