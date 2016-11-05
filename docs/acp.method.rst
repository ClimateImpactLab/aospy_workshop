
Approach to Climate Projections
-------------------------------

Aggregation of highly localized historical climate data from every county in the 
United States. 

1.  County level projections of daily temperature and precipitation by a three 
    step process.  For each Representative Concentration Pathway (8.5, 6.0, 4.5, 
    2.6) we constructed a probability distribution for GMST change. For these estimates, we assumed static SSP. 

2.  Joint spatio-temporal distribution of monthly temp and precip constructed 
    from CMIP5 models and downscaled (to local levels of resolution). This was 
    done by using the MAGICC Model. For the tails of distribution we created model 
    surrogates from wet and dry models in the CMIP5 archive. These model 
    surrogates, together with our 34 models from the CMIP5 archive compose our 
    set of climate realizations. The PDF of the distribution is based on the projections of 
    the models. 

    .. image:: imgs/smme.png


3.  Daily projections were constructed for each climate realization by 
    superimposing historical daily weather residuals around monthly 
    climatologies from period 1981 - 2010. 


Impact Meta-Analysis
--------------------

From here, economic impacts in agriculture, energy, mortality, labor, crime and 
coastal property were computed for each county-level joint realization of 
temperature and precipitation. Our response functions were derived using a 
Bayesian meta-analysis of the latest econometric impact research.

That system is described here: `DMAS <http://dmas.berkeley.edu/>`_


Impact Calculations
-------------------

Impacts were calculated at the county-level for each year 2000-2099 and reported 
as changes from 2012. 



Links for further information
----------------------------- 

`Science Article <https://dl.dropboxusercontent.com/u/3011470/Publications/CARLETON_HSIANG_SCIENCE_2016_W_SI.pdf>`_

`Climate Econometrics <http://www.nber.org/papers/w22181>`_

`Climate Prospectus <http://climateprospectus.org/>`_


