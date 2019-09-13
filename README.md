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

### Creating an environment
In order to create your own environment, use:
```bash
conda create -yn fishtest
```

Activatig:
```bash
conda activate fishtest
```

Deactivating:
```bash
conda deactivate
```
