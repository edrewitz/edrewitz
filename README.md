## print("Hello World!") 

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![csharp](https://img.shields.io/badge/c%23-239120?style=for-the-badge&logo=dotnet&logoColor=white)

***My name is Eric J. Drewitz and I am both a Meteorologist (SUNY Oswego Class of 2016) and a self-taught software developer with a focus on data-flow, data-science and data-engineering. I mainly code in the Python Programming Language. New to learning C#.*** 

My work focuses on developing new Python libraries focusing on weather and climate. 

Current libraries I've developed and actively maintain are:

1) [**FireWxPy**](https://pypi.org/project/firewxpy/) - An open source library focused on fire weather analysis and forecasting.

<img width="200" alt="firewxpy logo" src="https://github.com/user-attachments/assets/27d7353c-89ae-4827-a1fb-0d64d80599ad"> ![image](https://github.com/user-attachments/assets/da1b43c0-2b6a-4a5c-9eb4-f08b30cab42b)

Anaconda Downloads: 

[![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/firewxpy.svg)](https://anaconda.org/conda-forge/firewxpy)

PIP Downloads:

![PyPI - Downloads](https://img.shields.io/pypi/dm/firewxpy)

The FireWxPy package provides the following extra functionality compared to existing packages:

i) A large selection of various weather graphics from various different data souces.
   - These weather graphics have a specific focus on fire weather. 

ii) Easy to use - the user sets the arguments in the function to their choosing and the functions do all the work including downloading, parsing and plotting the data. 
 
2) [**xmACIS2Py**](https://pypi.org/project/xmacis2py/) - An open source library focused on creating data visualizations of ACIS2 climate data (xmACIS2 in Python).

![image](https://github.com/user-attachments/assets/fb5ecdf9-bd51-4243-be7d-92af0952bfd8) ![image](https://github.com/user-attachments/assets/da1b43c0-2b6a-4a5c-9eb4-f08b30cab42b)

Anaconda Downloads:

[![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/xmacis2py.svg)](https://anaconda.org/conda-forge/xmacis2py)

PIP Downloads:

![PyPI - Downloads](https://img.shields.io/pypi/dm/xmacis2py)

The xmACIS2Py package provides the following extra functionality compared to existing packages:

i) User friendly - The user sets the parameters in the function to their choosing and the function does all the work - downloading, parsing and plotting the data.
 
ii) Users can easily create summary graphics for the various weather stations in the ACIS2 database. 
   
3) [**PyClimo**](https://pypi.org/project/pyclimo/) - An open source library for climate data analysis such as NCAR Reanalysis and PRISM data.

Anaconda Downloads:

[![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/pyclimo.svg)](https://anaconda.org/conda-forge/pyclimo)

 PIP Downloads:

 ![PyPI - Downloads](https://img.shields.io/pypi/dm/pyclimo)

<img width="200" height="150" alt="climate" src="https://github.com/edrewitz/PyClimo/blob/main/climate.jpg?raw=true"> ![image](https://github.com/user-attachments/assets/da1b43c0-2b6a-4a5c-9eb4-f08b30cab42b)

The PyClimo package provides the following extra functionality compared to existing packages:

i) User friendly - The user sets the parameters in the function to their choosing and the function does all the work - downloading, parsing and plotting the data.

ii) Plots the period mean of the dataset.

iii) Utilizes the [xeofs library](https://pypi.org/project/xeofs/) functionality to perform Empirical Orthogonal Function (EOF) Analysis on the various netCDF4 datasets.

iv) Accesses NCAR Reanalysis data and PRISM Climate Group data. 

4) [**WxData**](https://pypi.org/project/wxdata/) - An open source library that downloads, pre-processes and post-processes a medley of open-source weather data.

![weather icon](https://github.com/edrewitz/wxdata/blob/main/icons/weather%20icon.jpg) ![python icon](https://github.com/edrewitz/wxdata/blob/main/icons/python%20logo.png)

Anaconda Downloads

[![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/wxdata.svg)](https://anaconda.org/conda-forge/wxdata)


PIP Downloads:

![PyPI - Downloads](https://img.shields.io/pypi/dm/wxdata)

The WxData package provides the following extra functionality compared to existing packages for downloading weather data:

i) Friendly for users working on VPN/PROXY connections.

ii) Post-processes GRIB data by remapping the GRIB variable keys into variable keys that are in plain language. 

iii) Has a scanner that checks if the data files on your PC are up to date with those on the data server. This helps newer developers avoid temporary IP address bans from data servers by avoiding excessive/repetative data downloading.

iv) Preserves system memory by clearing out old data files with each new data download combined with the option for users to clear out their computer's recycle/trash bin with each run.


5) [**shapeography**](https://pypi.org/project/shapeography/) - A Python library that both a client that downloads various shapefiles and GEOJSON files from the web and processes these geometry files. Users can also process locally hosted shapefiles and GEOJSON files. Also works for those on VPN/PROXY connections.

<img src="https://github.com/edrewitz/shapeography/blob/main/Thumbnails/86506Livingston-Rev-Base.jpg?raw=true" width="200" alt="Alt text" /> <img src="https://github.com/edrewitz/WxData/blob/1be590e9a16033974a592d8cf99f3cd521f95e0b/icons/python%20logo.png?raw=true" width="200" alt="Alt text" />

Anaconda Downloads:

[![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/shapeography.svg)](https://anaconda.org/conda-forge/shapeography)

PIP Downloads:

![PyPI - Downloads](https://img.shields.io/pypi/dm/shapeography)

shapeography is a package that has a client to manage shapefiles/GEOJSON files. The client supports users on VPN/PROXY connections and is geared towards automation. 

shapeography also has functions to unzip shapefiles/GEOJSON files (supports .zip, .gz, .tar and .tar.gz)

shapeography also extracts the raster data and returns a geopandas.GeoDataFrame of geometry data and full datasets. 

***I hope you find my libraries useful whether you are an operational meteorologist, researcher, academic etc. My goal is to make computer programming easier for fellow meteorologists, atmospheric scientists and climate scientists alike.*** 
<!--
**edrewitz/edrewitz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
