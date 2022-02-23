### Data goes in this directory, but not into the repo

Run from the project root, and any reference to training/testing or other data should reference this directory path.

example:  my_data_file = 'data/myfile.csv'
          pd.read_csv(my_data_file)

