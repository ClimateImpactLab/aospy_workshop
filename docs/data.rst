The future of our system

Our goal is to make the analysis of Climate and Econometric data feel trivial over large datasets. 

Our task is to remove the complexity of computing terrabytes of data so the econometricians can do their analysis. We want to acclerate the time it takes for econometricians to prototype, test and analyse their climate impact functions. 

So we've been researching and thinking about the next iteration of our data pipeline. And we 
are very excited and interested to see how we can fully implement xarray and dask for this.

We imagine the future stack to be 

1. Python or other for Econometrics (currently Stata :-( )

2. Xarray as core for all data analysis due to named indexing, high dimensionality, metadata inclusion. 

3. Dask Due to size of data we want to use dask to handle distributed computation of our climate impacts. We want to enable exploration for our researchers so they can take diagnostics of small subsets of the analysis (for a given scenario, region, or climate model).


4. We 


Questions
---------


1. Is there a better way of storing our structured data. Right now netCDF is our core data model
2. This limits how we can read data. 

3. Can we use Dask outside calling it from xarray. Can we use dask to create xarray objects from S3 `Internal Data Ingestion <http://dask.pydata.org/en/latest/bytes.html>`_