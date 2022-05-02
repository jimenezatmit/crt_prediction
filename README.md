# Predicting Cognitive Reflection from Digital Fingerprints

Please read below for a high-level explanation of code structure. **All relevant code and results are stored in the /pipeline folder.**

**Scripts**
1. *data_processing.ipynb*: This script walks the user through creating the input dataframe and performing relevant pre-processing and exclusions, **which must be completed before running the pipeline**. 
2. *run_pipeline.ipynb*: This script runs the pipeline end-to-end and saves all outputs to the */data* and */results* folders. For a visualization of the pipeline, see **schematic.pdf**.

**Folders**
1. */data*: This folder stores both (1) the input dataframes and (2) the data statistics from *data_processing.ipynb*.
2. */results*: This folder stores the individual, umbrella, and combined feature predictions from *run_pipeline.ipynb*.
3. */pipeline_components*: This folder contains individual scripts for all pipeline and data-preprocessing components.

**How to run pipeline**
1. To run the pipeline, first read and run through *data_processing.ipynb* to create the input data frame. 
2. Then, read and run through *run_pipeline.ipynb* to run the data frame through the pipeline.

*Raw data files are not uploaded onto Github for privacy purposes.*
