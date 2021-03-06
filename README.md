## Getting Set Up

To use Jupyter (Python) notebooks in the cloud, your options are:
- [Microsoft Azure Notebooks](https://notebooks.azure.com/): there is an option to import directly from a GitHub repository, for which you can simply use this URL.
- [Google Colaboratory](https://colab.research.google.com/): this requires you to upload data manually, so it is somewhat less useful than the above.

Alternatively, if you'd like to install Python and Jupyter on your computer, I would suggest using the [Anaconda](https://www.anaconda.com/) distribution, which is quite stable and supports all major platforms. After installing it, run either the Jupyter Notebook or JupyterLab. Finally, download the files in the repository and open the desired notebook.

You can get Stata from the Pitt software download service, and installation should be relatively painless.

## Notebooks

For now we have three mini lessons, each implemented in Python/Jupyter (`.ipynb`) and Stata (`.do`):
- `1_Introduction`: loading in, reshaping, and plotting single data series and panel data.
- `2_Analysis`: panel data with multiple series, as well as advanced visualization.
- `3_Merging_Data`: merging together two different datasets by country and year.

## Data

Your best bet for many types of data is [FRED](https://fred.stlouisfed.org/). Check it out! Here's what's in the `data` directory:
- `GDPCA.xls`: Annual Real GDP for the US (FRED)
- `mpd2018.xlsx`: Maddison Project full country data
- `mpd2018_region_data.xlsx`: Maddison Project regional data
- `pwt90.xlsx`: Penn World Tables (9.0) full country data
- `world_bank_gini.xls`: World Bank inequality data (Gini coefficient)
