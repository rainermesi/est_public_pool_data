# Estonian Public Pool Water Quality Data

Wrangling water quality data out of public domain xml documents with python

Jupyter notebook: [water_quality_02.ipynb](https://github.com/rainermesi/est_public_pool_data/blob/master/water_quality_02.ipynb)

Pools and test results: [est_pool_proc_data.csv](https://github.com/rainermesi/est_public_pool_data/blob/master/est_pool_proc_data.csv)

Columns:
|column name | description |
|--------|------------------------------------------------|
|pool_id:| unique id for each pool in a recreation center |
|pool_nm:| pool name (in Estonian) |
|test_dt:| date of procedure |
|proc_id:| unique id for procedure |
|proc_rs:| procedure result (vastab nõuetele - test passed ; ei vasta nõuetele - test not passed) |
|proc_test_nm:| name of test in a procedure |
|proc_test_rs:| result of test in a procedure |
|proc_test_val:| value of test in a procedure |
|proc_test_unit:| mesuring unit of test value |

Recreation center names: [est_pool_data.csv](https://github.com/rainermesi/est_public_pool_data/blob/master/est_pool_data.csv)

There is more data in the source file, but at the moment this csv can only be used to link individual pool id's to the recreation center they are part of.
