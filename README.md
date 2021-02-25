# nonrecovery-nepal

This repository contains the source code and *some* of the data to replicate key results from the following paper:

*<u>insert paper citation*</u>

## Licensing and availability

The code and the data are both licensed under the CC-by-NC-SA license. Feel free to use either based on the terms and conditions listed in the LICENSE.md file in the code and data's respective folders and reference the above paper. We intend this code to be used for NON-COMMERCIAL uses, if you'd like to use either for commercial uses, please contact Sabine Loos at  [sloos@stanford.edu](mailto::sloos@stanford.edu).

### Data availability

**Predictors of non-recovery** The prepared dataframe of the final predictors used to estimate non-recovery are included in the .rds file *pred_grid_nonrecovery.rds*. The sources for the original data used in this dataframe are included in the Supplementary Information of the above paper.

**Surveyed reconstruction data** Because the survey data used in this paper at this resolution is proprietary to The Asia Foundation, we cannot make the data available at this time. To access the data, please contact The Asia Foundation directly. 

## Using the code

There are two main scripts in repository. 

1. The first is *variable_selection.R*. Run this code to carry out the automatic variable selection. Warning that this will take an hour or so to run.
2. The second is *model-nonrecovery.R*. This pulls together the results from *variable_selection.R* and builds all the results figures shown in the paper.

To run both *variable_selection.R* and knit *model-nonrecovery.R*, run the "run.sh" file in your command line.

### Required Operating Environment

This code was developed using R version 3.6.1. All necessary packages for this code to run are included in the "*install.R*" file. 

Copyright (c) Sabine Loos, 2021.
