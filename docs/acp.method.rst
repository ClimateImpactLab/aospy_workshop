
The ACP began in 2013 as part of the 
`Risky Business Project <http://riskybusiness.org/>`_ with the goal of 
understanding the economic risks of climate change to the US economy. 

Approach to Climate Projections
-------------------------------

Aggregation of highly localized historical climate data from every county in the 
United States. 

1.  County level projections of daily temperature and precipitation by a three 
    step process.  For each Representative Concentration Pathway (8.5, 6.0, 4.5, 
    2.6) we constructed a probability distribution for GMST change (what 
    simplified climate model went into this?). For these estimates, we assumed 
    static SSP. 

2.  Joint spatio-temporal distribution of monthly temp and precip constructed 
    from CMIP5 models and downscaled (to local levels of resolution). This is 
    done by using the MAGICC Model. For the tails of the model, we created model 
    surrogates from wet and dry models in the CMIP5 archive. These model 
    surrogates, together with our 34 models from the CMIP5 archive compose our 
    set realizations. The PDF of the distribution is based on the projections of 
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

`DMAS <http://dmas.berkeley.edu/>`_


Impact Calculations
-------------------

Impacts are calculated at the county-level for each year 2000-2099 and reported 
as changes from 2012. State and national impacts are weighted over counties. For 
each RCP and climate model we ran Monte Carlo to account for economic and 
weather uncertainty. Impact distributions are represented as empirical 
distribution functions.    

.. image:: imgs/response.png


Links for further information
----------------------------- 


Add background information for people to follow up on. 