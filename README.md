# PANDAS
Using Anaconda and PANDAS.  

Adding conda to the PATH using fish:
```bash
set -U fish_user_paths ~/bin/anaconda3/bin $fish_user_paths
```

To remove, use
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

To use conda's env:
```bash
conda activate fishtest
```

After:
```bash
conda deactivate
```
