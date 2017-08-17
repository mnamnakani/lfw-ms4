 # THE LFW-MS4 DATASET

Description
--------------------------
Consists of all the subjects that have at least four samples in the training subset of View-1 from the LFW database [1]. All the used images were aligned using deep funnelling [2]. 
 
Files
--------------------------
"lfw_ms4_dataset_subjects.csv" contains a list with the 430 subjects that compose the LFW-MS4 dataset. For each subject, the samples 1 to 4 (in sequence) were extracted from [2].

"lfw_ms4_dataset_gt_rates.csv" contains the ground truth relative rates of 24 facial attributes for the LFW-MS4 subjects. The relative rates of each attribute were deduced based on the labels collected in [3].

"comparative labels/relation_matrix_f_*.csv" consists of the pairwise comparisons between the 430 subjects of the LFW-MS4 dataset as a matrix where an entry (i,j) represents a comparison between subjects i and j. The values -1,0, and 1 are associated with the "Less", "Same", and "More" labels respectively, and the value 5 represents the "Don't know" label. The integer that follows 'f' in the file name represents the attribute index is in Table 1 in [3].

For any questions
--------------------------
 Author: Nawaf Y Almudhahka (University of Southampton) 
 almudhahka@gmail.com 
 nya1g14@ecs.soton.ac.uk
--------------------------


References
--------------------------
[1] Huang, Gary B., et al. Labeled faces in the wild: A database for studying face recognition in unconstrained environments. Vol. 1. No. 2. Technical Report 07-49, University of Massachusetts, Amherst, 2007.

[2] Huang, Gary, et al. "Learning to align from scratch." Advances in Neural Information Processing Systems. 2012.

[3] Almudhahka, Nawaf Y., Mark S. Nixon, and Jonathon S. Hare. "Unconstrained human identification using comparative facial soft biometrics." Biometrics Theory, Applications and Systems (BTAS), 2016 IEEE 8th International Conference on. IEEE, 2016.
  
