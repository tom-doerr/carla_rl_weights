This repository contains checkpoint-files for the Sentdex/Carla-RL repository ( https://github.com/Sentdex/Carla-RL ).

You can extract the checkpoints using lrztar (`sudo apt-get install lrzip`):
```
lrztar -d 5_residual_CNN.tar.lrz        # extracts files to folder 'run1' 
lrztar -d 64x3_CNN.tar.lrz              # extracts files to folder 'run2'
```

The two networks were trained for roughly one week each on a GTX 1080ti.
