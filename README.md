Predicting Concrete Mix Compressive Strength Compliance from Mix Components

The dataset used to train the model is called 'Concrete_Data' and it is a csv
file.

Suppose we want to use the model after training to classify new mixtures:

  First, name the new data file 'new_data' and it has to be .csv file.
  This file must have variable in this order:'cement, slag, fly ash,
  coarse aggregates, fine aggregates, super, water', where column names is in
  the first row of csv file and data starts from second row.

  Then, have these two files in the directory python pointing at.

  Finally, run Jupyter Notebook.ipynb:
  1. will produce the results output inclued in the report in the notebook.
  2. and a new 'new_data' csv file with new column 'predicted compliance' containing results predicted by the best model recommended in the report.
	note: this will replace the existing 'new_data' file at the beginning of the run. 
