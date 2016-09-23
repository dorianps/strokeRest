# strokeRest

A sngle function to process fMRI resting state data in ANTsR. The function is optimized for use in stroke patients. The lesion mask you provide is used to remove the lesion when computing nuisance variables. The function can take registration matrices to a template and can automatically prodice for you the final connectome matrix. Multiple parcellation atlases can be passed as an argument (i.e., list(atlas1, atlas2) ) to obtain multiple connectomes at the same time.

Results are returned in a single list() varible. If you want to save this for later use, use the save.ANTsR() command.
