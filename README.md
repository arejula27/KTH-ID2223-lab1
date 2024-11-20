# KTH ID2223 Lab 1

This repository contains the code and automation for the first assignment of the ID2223 course.

The work is located in the `notebooks/ch3` folder. This assignment is divided into four files:

- **`1_air_quality_feature_backfill`**: Sets up the schema for the feature store on Hopsworks and performs the initial population.
- **`2_air_quality_feature_pipeline`**: Implements a pipeline to ingest data from external resources and update the feature store.
- **`3_air_quality_training_pipeline`**: Handles model training and verification.
- **`4_air_quality_batch_inference`**: Performs batch inference for the next 10 days.

You can view the results on the [dashboard](https://arejula27.github.io/KTH-ID2223-lab1/air-quality/).


We also did the sixth task, it involved changing all the files, we redefine the schema for the 'feature group' adding a new field. After that we created a new model using the newer data. On the inference file we had to modify tha prediction system, because the new predictions has a dependency on the previous day.
