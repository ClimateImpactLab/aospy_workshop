Current system


Our job is to make Econometric analysis feel trivial over large datasets. 

How to remove the complexity of computing terrabytes of data so they do their analysis

So we've been researching and thinking about the next iteration of our data pipeline. And we 
are very excited and interested to see how we can fully implement xarray and dask for this.

We imagine the future stack to be 

Scipy for econometrics, Xarray as core for all data analysis due to named indexing, high dimensionality, metadata inclusion. Due to size of data we want to use dask to handle out of memory computing