The tool was developed in Python using the Bokeh package on a Windows 10 machine. The tool is deployed using Heroku. 

To run locally without Heroku, download the lq_app folder.  Open the command prompt in the folder containing the lq_app folder, and type type:

bokeh serve lq_app --show

The Procfile, Procfile.windows, and requirements.txt file are used when deploying the tool on Heroku.

See https://devcenter.heroku.com/articles/getting-started-with-python#introduction for more information on how to deploy Python apps with Heroku.

---------------------------------
#Tool Purpose
How is Your City's Economy Unique?

Location Quotients (LQs) compare the proportion of a particular region's employment in a 
particular industry to the proportion of a larger reference area's employment in that 
same industry. An LQ of greater than 1 indicates that an industry has a higher 
concentration of employment in that region than in the overall reference area. An LQ of
less than 1 indicates that an industry has a lower concentration of employment in that 
region than in the overall reference area.

This chart shows 2016 LQs for each Metropolitan Statistical Area (MSA) in the U.S. with a 
reference area of all MSAs in the U.S. It conveys how concentrations in employment vary 
from city to city. These LQs are recalcualted from overall LQs provided by the Bureau of 
Labor Statistics (BLS) Quarterly Census of Employment and Wages.

Use the filters below to view LQs for different MSAs and different industry aggregation 
levels, ranging from supersector (larger groupings) down to NAICS 4-digit sector (smaller 
groupings). (NAICS: North American Industry Classification System)

These MSA LQs are recalculated from overall LQs provided by the Bureau of Labor 
Statistics (BLS) Quarterly Census of Employment and Wages. Government LQs are 
incorporated into the displayed industry aggregation levels too; these do not appear 
directly in the BLS data.

U.S. Bureau of Labor Statistics, 'Quarterly Census of Employment and Wages,' 26 June 
2017. www.bls.gov/cew/datatoc.htm.
