## Investigating the spatial variation of geospatial jobs in England in October and November, 2021
For the months, October and November, 2021, in order to see how geospatial jobs varied from one English region to another, job posts that contained the word `geospatial`(either in the job title or description) were [scraped from LinkedIn](), cleaned and stored in a csv file, in order to explore and visualize the data. 


### Data Sources
|Data type                        |Source                              |Component
|---------------------------------|----------------------------------- |--------------
|Spatial                          |[data.gov.uk](https://data.gov.uk/dataset/d310b2c5-5253-4bc2-a78d-f8240293119d/boundary-line) |Shapefile(.shp, .dbf, .prj, .shx)
|Non-spatial                      |Linkedin                            |Csv file(with the following columns:  `job_title`, `Company_name`, `Location`, `FILE_NAME`)


-------------------------------------------------------------------------------------------
References

[How to make a tabular legend in geopandas plot](https://stackoverflow.com/questions/44594956/how-to-make-tabular-legend-for-geopandas-plot)
