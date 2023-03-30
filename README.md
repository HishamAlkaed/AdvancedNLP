# AdvancedNLP

- In order to generate datasets for a specific set of capabilities, you must execute the `datasets_creation.ipynb` notebook sequentially. 
It is important to note that there must be a folder called `datasets` available to save the resulting data produced by this process. This folder should be on the same level as the notbook.

- Upon executing this notebook, specific datasets will be created for each capability, named data1 through data6. 
It is recommended that the user consults the `datasets_creation.ipynb` notebook for precise nomenclature and naming conventions of each test.

- In order to analyze and evaluate the effectiveness of these models on the generated datasets, run the 1 `running_models.ipynb` notebook. 
It is expected that the user create an `outputs` folder directory for the resulting output files generated as a result of this process. This folder should be on the same level as the notbook.

> NB: If you wish to inspect the datasets or the outputs, it is recommended to use Jupyter Lab or some similar text editor since those are json files and are read easier that way.
