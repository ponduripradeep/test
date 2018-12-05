├── bash_scripts
│   ├── csv_output.sh
│   ├── data_load.sh
│   ├── install_env.sh
│   └── oracle_to_aurora_pipeline.sh
├── input_files
│   ├── aurora_data_load_queries.yaml
│   ├── data_load.sh.sh
│   ├── environment.yml
│   ├── inp_validation_queries.csv
│   ├── logging.yaml
│   ├── neo4j_behavior_agg_queries.yaml
│   ├── neo4j_data_load_queries.yaml
│   ├── neo4j_data_queries.yaml
│   ├── parameters.yaml
│   └── runtime_validation_queries.yaml
├── logs
│   ├── behaviors_to_csv.log
│   ├── csv_to_aurora.log
│   ├── data_load_logs.log
│   ├── files.log
│   ├── neo4j_driver.log
│   ├── run_time_validation_logs.log
│   └── validation_logs.log
├── read_me
│   ├── 00_project_folder_prototype.md
│   ├── 01_environment_set_up.md
│   ├── 02_data_load.md
│   └── 03_behavior_agg.md
├── scripts
│   ├── aurora_data_load.py
│   ├── behavior_agg_to_csv.py
│   ├── global_functions.py
│   ├── __init__.py
│   ├── logging_setup.py
│   ├── missing_behav_agg.py
│   ├── neo4j_data_load.py
│   ├── neo4j_data_to_csv.py
│   ├── runtime_validations.py
│   └── tree.sh
└── tests
    └── unit_tests
        ├── inp_validation_queries.csv
        ├── neo4j_vs_oracle_behv_validation_report.csv
        ├── oracle_client
        │   ├── instantclient-basic-linux.x64-18.3.0.0.0dbru.zip
        │   └── instantclient-sdk-linux.x64-18.3.0.0.0dbru.zip
        ├── oracle_install.sh
        ├── test_global_functions.py
        ├── validation_readme.md
        ├── validation_script.py
        └── validations.py

8 directories, 44 files
