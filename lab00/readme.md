# **Process**
- Popular repos were searched on github based on stars.
- The repos were cloned to a local repository.
- The local files were checked if they were written in java by inspecting the filename for ".java" extention.
- A method signature was created using the repo name and the method name to check for duplicates.
- A total counter was set to collect the required number of data items (i.e. 20000 training items and 5000 testing items)
- The collected data was saved to the same .csv file with the specified column headers. The data was divided into train and test using the dataset_split coumn.

# **Data Statistics**
- Total collected methods = 25000
- Total training methods = 20000
- Total test methods = 50000
