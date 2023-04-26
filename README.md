# airflow
airflow playground

## Installation and running on a local machine

### usnig pip
* Go to https://github.com/apache/airflow#installing-from-pypi and follwo the instructions
* Next setup env variable: *AIRFLOW_HOME=$(pwd)*
* Run command: *airflow db init*
* Create user: *airflow user create....*
* Run webserver: *airflow webserver*
* Run scheduler: *airflow scheduler*