# ENSO project


The goal of the project is to study existing classifiers. Here are the different files contained in this project :\
- $sst.mnmean.nc$ is a netcdf file that you can open in python with the xarray library. It contains monthly mean sea surface temperature from the NOAA reanalysis\
- $mslp_coarse.nc$ contains atmospheric pressure above the PAcific Ocean.\
- $project_elnino.ipynb$ is a juyter notebook containing the project sibject/introduction.\
- $elnino.ipynb$ is the main jupyter notebook that is supposed to answer our problematic on the predactibility of El Nino phenomenon.

In a first approach, we interest ourselves in a classification approach, with a method similar to the LDA method. We used the $\textit{Nino sst Indices}$ explained in this article : https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni

For an unsupervised approach, with the Pricipal component method, we refer to this article : https://link.springer.com/article/10.1007/s00376-010-9173-5
