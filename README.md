# testing predicition model
__________________________

## Prerequisites:
```
run install_packages.R file from 'models/predict' directory
```
```
install package 'testthat'
```
### from test predict directory
```
run commands in the following order:
pytest -v test_fabfile.py
pytest -v test_conf.py
pytest -v test_etl.py
python insert_data.py
(to insert required data into the generated tsv)

Rscript run_tests.R
```
