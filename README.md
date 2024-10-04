# Machine Learning Tutorial - CSU and NCA&T

Tutorial materials of the python examples (.py), data (.csv,.nc), and jupyter notebooks (.ipynb) used in the Machine Learning Tutorial for Earth Scientists created by members of the Atmospheric Science Department at Colorado State University.

## Requirements & Specifications

### Code

Code is written in pytorch.

### Environment

This code was created to run in Google Colaboratory <https://colab.research.google.com/>. All you should need is a Google account.

Unless otherwise stated, code was additionally tested on local machines using the following environment.
```
conda create --name env-ml-tutorial-ncat python=3.12.0
conda activate env-ml-tutorial-ncat
pip install ipykernel
conda install numpy scipy pandas matplotlib xarray scikit-learn netCDF4 cartopy pytorch
conda install  palettable flake8  jupyterlab black jupyterlab_code_formatter
```

## Additional Information

### Credits

The majority of the materials were created by Ashley Dwyer, Devin McAfee, Marybeth Arcodia and Elizabeth A. Barnes.

### License

This project is licensed under an MIT license.
MIT © [Elizabeth A. Barnes](https://github.com/eabarnes1010)
