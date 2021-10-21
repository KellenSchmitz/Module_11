# Module_11

# Project Overview:
The project goal was to build a webpage and dynamic table to allow users to apply multiple filters to the UFO sighting records stored in the data.js file. 

# Results:

To filter results, just enter data into any one of the filter search fields. When the user clicks away from the input field, or hits enter, the table will automatically filter the results. Filters can be added sequentially to narrow down a table.
![image](https://user-images.githubusercontent.com/86166117/138336435-79f78ab0-faa1-4adf-9b0c-1191db37700b.png)

Adding a date would further narrow down this search to just two results.
![image](https://user-images.githubusercontent.com/86166117/138338268-b9af2b55-102a-471e-92b8-3c4e6a140a4a.png)

# Summary
The webpage has some drawbacks. One being the lack of data outside of the US and for periords other than January of 2010. The design does not allow for easy sorting of the avaible data - the user has to first use trial and error to find out that there are no records in years other than 2010, or records for sightings outside of the US.

There are a few improvements we would suggest.
  1.  For the filter, use a drop down which contains a list of the actual values held in the database. This will prevent users from searching for descriptions that don't exist
  2.  Have a totals or some form of summary for the table data.
  3.  Add a visual representation of the total and filtered data. As is, the filtered table does not provide insight into how it relates to the whole.
  4.  A map of observations and their frequency.
