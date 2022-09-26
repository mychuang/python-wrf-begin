# Installation

## Create new env & install package

The folloing command will create a new env named "pywrf", which uses python 3.7 & many lib will be installed. (matplotlib cartopy netcdf4 jupyter git ffmpeg wrf-python)

```shell
conda config --add channels conda-forge
conda create -n pywrf python=3.7 matplotlib cartopy netcdf4 jupyter git ffmpeg wrf-python
```


## 切換環境與測試

- 切換環境

  ```
  conda activate pywrf   
  ```

- 退出環境

  ```
  conda deactivate
  ```

- 驗證測試

  ```python
  import netCDF4
  import matplotlib
  import xarray
  import wrf
  ```

- 更多測試: Refer [0-verifyEnv](0-verifyEnv.ipynb)