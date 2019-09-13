# PANDAS
Using Anaconda and PANDAS.

Adding conda to the PATH using fish:
$ set -U fish_user_paths ~/bin/anaconda3/bin $fish_user_paths

To remove, use
$ echo fish_user_paths
$ set -U -e fish_user_paths[1]
Where 1 is the first line

creating an environment:
$ conda create -yn fishtest

To use conda's env:
$ conda activate fishtest
