Here we will discuss the steps needed to run scrapping codes.

As we all know when we scrape any website we will follow trial and error methods and many intermediate codes have been used and modified like generic function is coded 
and passed parameters like job title and job location. then function will build the URL and used for scraping the site and output file will be named accordingly.
(i.e. DataAnalyst_Jobs_Vancouver.csv).

1. Project_Scrapping_Part1.
-This code can be adjusted accordingly and URL will be generated based on user input. user can input job title and job location. links are generated accordingly and data is collected.

2. Creating_MasterLinks_Code.
-This job will create all required links and base URL's are hard coded and depending on number of pages we need to adjust parameters in for loop. this involves human intervention to successfully run this job.

3. ScrapeCode_From_MasterLinnks.
-The list created in above step will be input and data is collected and converted into dataframe and exported to given location.

4. Merging&Creating_CSV_File.
-This code take inputs from step1 & 3 , all the output files generated will be concatenated and creates final CSV file which includes required job information. Here we are also concatenating one external file from web which has job information.

Important Output Files Location.
-Final CSV file Scrapped Data. - Data Files\Final_Scrapped_Data.csv

** End of file **




