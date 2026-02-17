### Cahnges made in this fork
- Added files in `conf` and `data` folder to the installable files so that this package can be also installed in a non-editable way. 
- Added full "assembled" config for evaluation so that it is no longer necessary to download the dataset to get the evaluation config. Also adding a method `get_config_path` in `utils`to easily get the paths to the included config data.

# calvin_env



## Installation
```bash
git clone --recursive https://github.com/mees/calvin_env.git
cd calvin_env/tacto
pip install -e .
cd ..
pip install -e .
```
