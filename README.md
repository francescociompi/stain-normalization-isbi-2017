# The importantce of stain normalization (ISBI 2017 conference paper)
This repository contains stain normalization parameters and code used in the paper:

*F. Ciompi, O. Gessinnk, B. E. Bejnordi, G. Silva de Souza, A. Baidoshvili, G. Litjens, B. van Ginneken, I. Nagtegaal, J. van der Laak*, 
**The importance of stain normalization in colorectal tissue classification with convolutional networks**, IEEE International Symposium in Biomedical Imaging, 2017.


# Installation
Download the input images from this link: https://zenodo.org/record/53169/files/Kather_texture_2016_larger_images_10.zip and unzip it.
Adapt the path in apply_stain_normalization.py to point to the folder that contains the input images.

# Code example
```
python apply_stain_normalization.py
```

# Code to compute Look-up tables
The code that was used to compute the look-up table files used in this project can be found at this link: https://github.com/computationalpathologygroup/WSICS


