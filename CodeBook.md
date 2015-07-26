# Variables

* `x_train`, Training set.
* `y_train`, Training labels.
* `x_test`, Test set.
* `y_test`, Test labels.
* `subject_train` 
* `subject_test` 
* `x_data`, `y_data` and `subject_data` merge the previous datasets.
* `features` contains the correct names for the `x_data` dataset
* `mean_and_std_features`, a numeric vector used to extract the desired data.
* A similar approach is taken with activity names through the `activities` variable.
* `all_data` merges `x_data`, `y_data` and `subject_data` in a big dataset.
*`averages_data` contains the relevant averages which will be later stored in a `.txt` file. 
*`ddply()` from the plyr package is used to apply `colMeans()` and ease the development.
