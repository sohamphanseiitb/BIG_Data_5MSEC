# Big Data Analysis of NASA's 5 Millenium Solar Eclipse Database
Authors: [Soham S. Phanse](mailto:19D170030@iitb.ac.in) [1], 

[1] Department of Aerospace Engineering, Indian Institute of Technology Bombay

[![DOI](https://zenodo.org/badge/432452134.svg)](https://zenodo.org/badge/latestdoi/432452134)

## Abstract
Solar eclipses are a topic of interest among astronomers, astrologers and the general public as well. There were and will be about 11898 eclipses in the 5 millennia from 2000 BC to 3000 AD. Data visualization and regression techniques offer a deep insight into how various parameters of a solar eclipse are related to each other. Physical models can be verified and can be updated based on the insights gained from the analysis. The study covers the major aspects of data analysis including data cleaning, pre-processing, EDA, distribution fitting, regression and machine learning based data analytics. 

## The Database
A glimpse of the Database we have processed from the original can be seen here:

| Catalog_No. | Canon_Plate | Year_(t=0@0AD) | Month | Date | Days_from_the_last_eclipse | TDGE_from_00:00 | DT_(s) | Luna_Num | Saros_Num | Eclipse_Type | Gamma | Eclipse_Magnitude | Latitude | Longitude | Sun_Alt | Sun_Az | path_width | Total_Central_Duration_(s) | 
| :-----------: | :-----------: | :--------------: | :-----: | :----: | :--------------------------: | :---------------: | :------: | :--------: | :---------: | :------------: | :-----: | :-----------------: | :--------: | :---------: | :-------: | :------: | :----------: | :--------------------------: | 
| 1 | 1 | -1999 | 6 | 12 | 0 | 11691 | 46438 | -49456 | 5 | T | -0.2701 | 1.0733 | 6.0 | -33.3 | 74.0 | 344 | 247.0 | 397.0 | 
| 2 | 1 | -1999 | 12 | 5 | 176 | 85523 | 46426 | -49450 | 10 | A | -0.2317 | 0.9382 | -32.9 | 10.8 | 76.0 | 21 | 236.0 | 404.0 | 
| 3 | 1 | -1998 | 6 | 1 | 187 | 65356 | 46415 | -49444 | 15 | T | 0.4994 | 1.0284 | 46.2 | 83.4 | 60.0 | 151 | 111.0 | 135.0 | 
| 4 | 1 | -1998 | 11 | 25 | 177 | 21423 | 46403 | -49438 | 20 | A | -0.9045 | 0.9806 | -67.8 | -143.8 | 25.0 | 74 | 162.0 | 74.0 | 
| 5 | 1 | -1997 | 4 | 22 | 217 | 47996 | 46393 | -49433 | -13 | P | -1.4669999999999999 | 0.1611 | -60.6 | -106.4 | nan | 281 | nan | nan | 

## Analysis
The Analysis, data visualization can be found in the [report](https://github.com/sohamphanseiitb/Big_data_analysis_NASA_5-Millenia-Solar-Eclipses/blob/main/big_data_analysis_of_NASA's_5_millenium_solar_eclipse_database.pdf) and are documented in detail. The codes can be found [here](https://github.com/sohamphanseiitb/Big_data_analysis_NASA_5-Millenia-Solar-Eclipses/blob/main/big_data_analysis_of_NASA's_5_Millenium_Solar_Eclipse_codes.ipynb).

## References
1.	“Eclipse Predictions by Fred Espenak and Jean Meeus (NASA's GSFC)”, NASA Technical Publication TP-2006-21414, 2009, https://eclipse.gsfc.nasa.gov/SEcat5/catalog.html,Accessed November 4, 2021
2. NASA GSFC. “NASA - Key to Catalog of Solar Eclipses.” NASA - Key to Catalog of Solar Eclipses, 2007, https://eclipse.gsfc.nasa.gov/SEcat5/SEcatkey.html. Accessed 25 November 2021.
3. “Ring of fire: Visualizing 5,000 years of solar eclipses.” Ring of fire: Visualizing 5,000 years of solar eclipses, SAS Blogs, 19 July 2019, https://blogs.sas.com/content/sascom/2019/07/19/ring-of-fire-visualizing-5000-years-of-solar-eclipses/. Accessed 25 11 2021
4. Harris, C.R., Millman, K.J., van der Walt, S.J. et al. Array programming with NumPy. Nature 585, 357–362 (2020). DOI: 10.1038/s41586-020-2649-2. (Publisher link).
5. Pauli Virtanen, Ralf Gommers, Travis E. Oliphant, Matt Haberland, Tyler Reddy, David Cournapeau, Evgeni Burovski, Pearu Peterson, Warren Weckesser, Jonathan Bright, Stéfan J. van der Walt, Matthew Brett, Joshua Wilson, K. Jarrod Millman, Nikolay Mayorov, Andrew R. J. Nelson, Eric Jones, Robert Kern, Eric Larson, CJ Carey, İlhan Polat, Yu Feng, Eric W. Moore, Jake VanderPlas, Denis Laxalde, Josef Perktold, Robert Cimrman, Ian Henriksen, E.A. Quintero, Charles R Harris, Anne M. Archibald, Antônio H. Ribeiro, Fabian Pedregosa, Paul van Mulbregt, and SciPy 1.0 Contributors. (2020) SciPy 1.0: Fundamental Algorithms for Scientific Computing in Python. Nature Methods, 17(3), 261-272.
6. J. D. Hunter, "Matplotlib: A 2D Graphics Environment", Computing in Science & Engineering, vol. 9, no. 3, pp. 90-95, 2007.
7. Michael L. Waskom (2021). seaborn: statistical data visualization. Journal of Open Source Software, 6(60), 3021.
8. Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J., Passos, D., Brucher, M., Perrot, M., & Duchesnay, E. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825–2830.
