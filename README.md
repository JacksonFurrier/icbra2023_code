# 3D Volumetric left ventricle segmentation of MPI SPECT images with self-supervised learning


Project Organization
------------

    ├── readme.md                      
    ├── experiments                             <- YAML file based configuration files to run experiments
    ├── notebooks                               <- Jupyter playbooks for initial experiments and code writing
    ├── logger.py                               <- Basic logger for Neptune.ml
    ├── models.py                               <- Model definitions for both SSL and supervised models
    ├── ssl_jigsaw_puzzle.py                    <- SSL algorithm to solve jigsaw puzzles pretext tasks
    ├── ssl_relative_patch_location.py          <- SSL algorithm to solve the relative patch location pretext tasks
    ├── supervised_training.py                  <- algorithm for supervised training on the target task after SSL
    ├── utils.py                                <- utility functions
