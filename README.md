# AdvancedNLP

In order to generate datasets for a specific set of capabilities, you must execute the datasets_creation notebook sequentially. 
It is important to note that there must be a folder called "datasets" available to save the resulting data produced by this process.

Upon executing this notebook, specific datasets will be created for each capability, named data1 through data6. 
It is recommended that the user consults the datasets_creation.ipynb notebook for precise nomenclature and naming conventions of each test.

In order to analyze and evaluate the effectiveness of these models on the generated datasets, it is necessary to run the running_models notebook. 
It is expected that the user create an "outputs" folder directory for the resulting output files generated as a result of this process.

If you wish to inspect the datasets or the outputs, it is recommended to used Jupyter Lab since those are json files and are read easier that way.
