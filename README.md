# implicitly_abusive_comparisons

This package contains supplementary notes and the new resources created for the paper "Implicitly Abusive Comparisons -- A New Dataset and Linguistic Analysis".


Here is a description of the content of the different subdirectories:

# *Guidelines*:
These are guidelines of the different subtasks that were carried out as part of creating the dataset of abusive comparisons.
For each of these subtasks, the crowdworkers were given an external URL to these guidelines as pdf. This allowed them to browse the guidelines while working on the task. (Thus we wanted to help crowdworkers clarifying open questions that arised during working on a subtask. Several crowdworkers explicitly mentioned those external pdf documents as helpful in the feedback session concluding each subtask.)

Since these pdf documents were exactly those documents given to the crowdworkers, there are slight deviations in terminology. For the paper, we changed the terminology to be more in line with the terminology that is used in previous research papers. We did not use that terminology in the surveys since we felt that some terms were less accessible or self-explanatory to laymen (as represented by our crowdworkers):
- abusive comparisons: in the guidelines, they are called "insulting comparisons"
- non-abusive comparisons: in the guidelines, they are called "negative comparisons"

# *Dataset*:

We provide two versions of the dataset:

goldstandard.txt
This is the first version is the version that we used for all our experiments in the paper. The file also includes all manually extracted features in separated columns

goldstandard.revised.txt
This is the second version contains the same comparisons as the first version. However, the language was corrected. (For more information on this version and motivation why we used the original version in our experiments, please see the supplementary notes.)
This file does not include the manually extracted features. Since our revision focused on spelling and syntax, the label of those features remains the same in both versions.


fold1.txt, fold2.txt, fold3.txt, fold4.txt, fold5.txt:
The 5 folds used in our experiments (5-fold crossvalidation).


# *contact information*

Please direct any questions that you have about this software to Michael Wiegand at Alpen-Adria Universitaet Klagenfurt.

Michael Wiegand email: michael.wiegand@aau.at

# *reference*

M. Wiegand, M. Geulig, J. Ruppenhofer: "Implicitly Abusive Comparisons -- A New Dataset and Linguistic Analysis", in EACL, 2021.