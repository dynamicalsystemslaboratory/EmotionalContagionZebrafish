# EmotionalContagionZebrafish
Experimental Data for the manuscript on Collective Emotional Contagion in Zebrafish

There are three files; namely, Data.xls, Data_Condition_Singles.mat, and Data_Condition_Groups.mat

The file Data.xls contains the scored behavioral metrics. More details of this data are provided in the first sheet of the file

The other two files Data_Condition_Singles.mat, and Data_Condition_Groups.mat contain the tracked swimming trajectories corresponding to the experimental data of the two conditions: Singles and Groups. The files are .mat and should be opened in Matlab.

This files contain a cell array with 3 entires corresponding to each citalopram concentration.
That is Data_Condition_Singles.mat contains an array TS1 where TS1{1} contains the data corresponding to 0 mg/L, 
TS1{2} contains the data corresponding to 30 mg/L, and TS1{3} contains the data corresponding to 100 mg/L

Then inside each entry TS1{} there are 12 additional entries corresponding to the 12 experimental trials for each Citalopram treatment
Each experimental trial contains  four time series of (x,y) coordinates and velocities v_x, v_y.
Each time series consist of 18,000 samples (sampling of 1/30 s) corresponding to the total experimental time of 10 min



Data_Condition_Groups.mat contains 5 arrays (TSG1,TSG2,TSG3,TSG4,TSG5) corresponding to data of 5 fish for each of the 12 trials at each Citalopram concentration.
Each of these five arrays follow the same structure explained before.
The TSG1 correspond to the treated individual in the group
