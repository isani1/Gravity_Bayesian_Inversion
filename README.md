% ***************************************************************
% *** Help file for running all codes
% *** Originated by:
% ***       Miss. Isani Saha (email: isani.saha.2000@gmail.com)
% ***       Dr. Chandra Prakash Dubey (email:p.dubey48@gmail.com)
% ***       Indian Institute of Technology Kharagpur
% ***       Kharagpur, West Bengal
% ****************************************************************
This is a help file for a description of all Data, Source Code, and Subroutine used for the implementation of our present paper 
“A Bayesian Gaussian Process Framework for the Discrete Inversion of 2D Gravity Data: Applications to the West Korea and Godavari Basins”

(Copy all set of files including data in one folder and run)

	1. Data Files
		a. Gravity_z.csv
		b. Ash layer.xlsx
		c. BASEMENT TOP DEPTH.xlsx
		d. Fault1.xlsx
		e. Fault2.xlsx
		f. x_obs_Godavari.dat
		g. gravity_anomaly_Godavari.dat
		h. depth_Zhou2012_3a.dat
		
	File (a) is the data for observed gravity anomaly of West Korea Basin.
        File (b) is the prior depth information data of the bottom of the top layer (Miocene Sediment) of the West Korea Basin along the profile (estimated by previous authors).
        File (c) is the prior depth information data of the Basement top of the West Korea Basin along the profile (estimated by previous authors).
        File (d) is the prior depth information data of Fault between Western and Central sub-basin of the West Korea Basin along the profile (estimated by previous authors).
        File (e) is the prior depth information data of Fault between Eastern and Central sub-basin of the West Korea Basin along the profile (estimated by previous authors).
	File (f) is the observation point data for observed gravity anomaly of Godavari River Valley Basin.
        File (g) is the data for observed gravity anomaly of Godavari River Valley Basin.
        File (h) is the depth profile data of Godavari River Valley Basin.
	
	2. Source Codes
    a. Codes_1st_Figure.ipynb
		b. 2_Prisms_Gradient_Descent_2026.ipynb
		c. 2_Prisms_Global_Optimization.ipynb
		d. Constant_Den_2026.ipynb
		e. Lat_Vary_2026.ipynb
    f. Resolution_Analysis.ipynb
		g. Ver_Lat_Varying_2026.ipynb
    h. Dipping_Layer_2026.ipynb
		i. West_Korea_Basin.ipynb
		j. Godavari_Data.ipynb
    k. Hyperparameter_tuning.ipynb
			
	a. Codes_1st_Figure.ipynb - It calculates the Bayesian inversion algorithm for a simple function and generates figure 1b.   
	
	b. 2_Prisms_Gradient_Descent_2026.ipynb- It calculates the inversion of gravity anomaly for two synthetic prisms with noise using Gradient Descent approach. Output of the file shown in figure 3(a,b,c). 

	c. 2_Prisms_Global_Optimization.ipynb- It calculates the inversion of gravity anomaly for two synthetic prisms with noise by Bayesian Inference using Structural GP regression, Active Learning using Structural GP and Bayesian Inversion using EI. Outputs of the file shown in figure 4(a,b,c).  

	d. Constant_Den_2026.ipynb- It calculates the inversion of gravity anomaly for a two-layer synthetic sedimentary basin having constant density contrast with noise case using by Bayesian Inference using Structural GP regression, Active Learning using Structural GP and Bayesian Inversion using EI. Outputs of the file shown in figures 5(a,b,c,d,e), 6(a,b,c,d,e), 7(a,b,c,d), 8(a,b,c,d), Supporting document figures (S 11,12,13,14, 15). 

	e. Lat_Vary_2026.ipynb - It calculates the inversion of gravity anomaly for a two-layer synthetic sedimentary basin having laterally varying density contrast with noise case using by Bayesian Inference using Structural GP regression, Active Learning using Structural GP. Outputs are shown in figure 9(a,b,c,d,e,f)

   f. Resolution_Analysis.ipynb - It does the analysis of how to select control points (i.e. model dimension) using Check-board analysis, along with inversion for high dimensional high resolution models. Outputs of the file shown in figures 10, Supporting document figures ( S - 3,4,5,6,7,8,9,10)

	g. Ver_Lat_Varying_2026.ipynb - It calculates the inversion of gravity anomaly for a one-layer synthetic sedimentary basin having vertical as well as laterally varying density contrast with noise case using Structural Gaussian Process regression approach. Output is shown in figure 11(a,b,c,d,e,f).

	h. Dipping_Layer_2026.ipynb - This code is for the inversion of Faulted dipping synthetic model by Bayesian Inversion using Structural GP regression. Outputs are shown in figure 12(a,b,c,d,e), 13(a,b,c,d,e,f).  

    i. West_Korea_Basin.ipynb - This code is for the inversion of the observed gravity anomaly along a 74 km profile of the Western Korea Basin using Structural GP regression, Active Learning using Structural GP. Output is shown in figure 14(a,b,c). 

    j. Godavari_Data.ipynb - This code is for the inversion of the observed gravity anomaly along a 37 km profile of the Godavari River Valley Basin using Structural GP regression. Output is shown in figure 15 and Supporting figures (S1 and S2).  

    k. Hyperparameter_tuning.ipynb - This code is for the section of hyper-parameter tuning part in the main paper. 



