# Code_for_Analysis_of_Sleep_Pattern_in_Flies
These codes analyzing the sleep pattern of individual flies can be run on MATLAB 2019a.
The Image Processing Toolbox should be installed at first.
## Main_1_Fly_Tracking_in_Each_Frame.m
This code detects the flies in each frame by evaluating the difference between the current image and the reconstructed background image.
## Main_2_Fly_Rest_detection.m
This code extracts the time interval in which the trajectory shows the fly is resting.
## Main_3_Fly_Sleep_Parameters_Estimation.m
This code estimates the sleep pattern parameters from the distribution of rest intervals. The power law exponent estimation adapts the MATLAB packages written by Aaron Clauset (A. Clauset, C. R. Shalizi, M. E. J. Newman, Power-Law Distributions in Empirical Data. Siam Rev 51, 661-703 (2009). 
## Main_4_Mathematical_Model_of_Sleep_Pattern.m
This code is for the simulation of the sleep process of the fly. The mathematical model considered a rest zone and sleep zone in the 2D grid (50x50). The time distribution of a random walker staying in the grid corresponds to the time distribution of the fly's rest behavior observed in the experiments.

