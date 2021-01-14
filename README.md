This repository contains checkpoint-files for the [Sentdex/Carla-RL repository](https://github.com/Sentdex/Carla-RL).
To successfully clone the repository you need to have [git-lfs](https://git-lfs.github.com/) (`sudo apt-get install git-lfs`) installed.
Alternatively you can download the weights [here](https://drive.google.com/drive/folders/1O5vxxT4V1EoduDrdGgwEXKe2-ag1uCiQ?usp=sharing).

You can extract the checkpoints using lrztar (`sudo apt-get install lrzip`):
```
lrztar -d 5_residual_CNN.tar.lrz        # extracts files to folder 'run1' 
lrztar -d 64x3_CNN.tar.lrz              # extracts files to folder 'run2'
```

The two networks were trained for roughly one week each on a GTX 1080ti.
