# IST303TeamProject_RFx
1. Team Members
  My team members are Mohammed Alfawzan and Akhilesh Prakash Rajeswari.

2. Come up with a concept for your application.

  ArcGIS allows users to leverage raster imagery data from data extraction, preparation, and visualization to analysis. On ArcGIS Pro, these imagery capabilities are implemented as a set of raster functions, divided into various categories based on their application fields. Each raster function has a set of parameters and associated required data types.
  For example, check out the documentation on the clip raster function (https://pro.arcgis.com/en/pro-app/latest/help/analysis/raster-functions/clip-function.htm). 
  **During each release of ArcGIS Pro, the parameters and required data types could change. We need a web database app that tracks the development of raster function changes across different releases of Pros. **
   
4. Identify all the relevant project stakeholders.

  The key stakeholders in this project are the Imagery/Raster team at Esri, and whoever uses Raster functions internally with Esri.

4. Create an initial set of project requirements expressed as user stories. User stories must have estimates of completion times.

  1) a database that provides an easy lookup of all raster functions and their parameters in all the previous ArcGIS Pro releases
  2) a comparison capability that generates the changes between releases
  3) a filtering and search capability that allows the user of the website to find the specific function they are looking for
  4) the ability to assign a raster function to a function owner (developer)
