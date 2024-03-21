# root


project_root/
│
├── data/
│   └── data.csv
│
├── models/
│   ├── scalar_model.pkl
│   ├── PCA.pkl
│   └── model.pickle
│
├── src/
│   ├── main.py
│   ├── tools/
│   │   ├── __init__.py
│   │   ├── data_loader.py
│   │   ├── preprocessor.py
│   │   ├── model_loader.py
│   │   ├── predictor.py
│   │   └── database_writer.py
│   │
│   ├── utils/
│   │   ├── __init__.py
│   │   └── helper.py
│   │
│   └── models/
│       ├── __init__.py
│       └── model_trainer.py
│
└── config/
    ├── spark_config.json
    └── database_config.json
