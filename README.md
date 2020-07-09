# Clustering_8_2_10
Springboard Mini Project on Clustering

This is a ipynb file while working on Domino several months bak.
This is a little incomplete. When I try to run it on my machine or
Google Colab or Paperspace it starts giving severeal errors in sequence,
such as 
- pandas sheetname keyword not defined - this is fixed by changing it to sheet_name
- ggplot is not installed - this is fixed by running !pip install ggplot
Then the following error occurs:
opt/conda/envs/springboard/lib/python3.7/site-packages/ggplot/utils.py in <module>
     79 
     80 date_types = (
---> 81     pd.tslib.Timestamp,
     82     pd.DatetimeIndex,
     83     pd.Period,
/opt/conda/envs/springboard/lib/python3.7/site-packages/pandas/__init__.py in __getattr__(name)
    260             return _SparseArray
    261 
--> 262         raise AttributeError(f"module 'pandas' has no attribute '{name}'")
    263 
    264 

AttributeError: module 'pandas' has no attribute 'tslib'
This was fixded in my local machione by replacing ---> 81     pd.tslib.Timestamp,
by pd._tslib.Timestamp

This luxury is not available in Paperspace or Google Colab

SO I am submitting my little incomplete notebook.

Thank you
Kejitan
