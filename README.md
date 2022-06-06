## Investigating the spatial variation of geospatial jobs in England in October and November, 2021
For the months, October and November, 2021, in order to see how geospatial jobs varied from one English region to another, job posts that contained the word `geospatial`(either in the job title or description) were [scraped from LinkedIn](https://github.com/Alyeko/Geospatial-jobs-England-OctNov-21/blob/main/Scraping%20geospatial%20jobs%20data%20from%20linkedin.ipynb), cleaned and stored in a csv file, in order to explore and visualize the data. 


### Data Sources
|Data type                        |Source                              |Component
|---------------------------------|----------------------------------- |--------------
|Spatial                          |[data.gov.uk](https://data.gov.uk/dataset/d310b2c5-5253-4bc2-a78d-f8240293119d/boundary-line) |Shapefile(.shp, .dbf, .prj, .shx)
|Non-spatial                      |Linkedin                            |Csv file(with the following columns:  `job_title`, `Company_name`, `Location`, `FILE_NAME`)


-------------------------------------------------------------------------------------------
References

[LinkedIn job scraping with python](https://youtu.be/X9OXAV7SGmM)

[How to make a tabular legend in geopandas plot](https://stackoverflow.com/questions/44594956/how-to-make-tabular-legend-for-geopandas-plot)
