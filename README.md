1. Creating Project structure

   ```bash
   CONCRET-STRENGTH
   ├── config
   |   ├──config.yaml
   |   ├──model.yaml
   │   └──schema.yaml
   ├── project-name
   |   ├──component
   |   |  ├──_init_.py
   |   |  ├──data_eda.py
   |   |  ├──data_ingestion.py
   |   |  ├──data_transformation.py
   |   |  ├──data_validation.py
   |   |  ├──model_evaluation.py
   |   |  ├──model_pusher.py
   |   |  └──model_trainer.py
   |   ├──config
   |   |  ├──_init_.py
   |   |  └──configuration.py
   |   ├──constant
   |   |  └──_init_.py
   |   ├──entity
   |   |  ├──_init_.py
   |   |  ├──artifact_entity.py
   |   |  └──config_entity.py
   |   ├──exception
   |   |  └──_init_.py
   |   ├──logger
   |   |  └──_init_.py
   |   ├──pipeline
   |   |  ├──_init_.py
   |   |  └──pipeline.py
   │   └──util
   |   |  ├──_init_.py
   |   |  └──util.py
   |   └──_init_.py
   ├── .github
   |   └──workflows
   |      └──main.yaml
   |── notebooks
   |── app.py
   |── trial.py
   |── requirement.txt
   |── setup.py
   |── Dockerfile
   |── .dockerignore
   └── README.md
   ```

   3. 