# Land-Cover-Analysis
Use a supervised classification to predict land cover 

About these files

File naming convention describes what the script does followed by a number indicating the order in which they should be run. 

ImportData-1: Loads libraries, imports watershed shapefile and landsat image. Formats data to prepare for analysis. 

TrainPoints-2: Manually click points on satellite imagery and write a shapefile of points (can skip this script once you've created a training dataset you are happy with)

CoverClassification-3: Partition trainiing points into a training and testing dataset, extract band information at each point, use classification tree to build a model, predict land cover across entire raster, and assess the accuracy of the model. 
SubwatershedAssessment-4: Examine land cover types within sub-watersheds. 

CoverBarplots-5: Creates a barplot showing land cover breakdown by sub-watershed 

Optional code- this file has code to visualize landsat imagery using RGB and near infrared bands. It also calculates NDVI values and plots them. Example code to save rasters of predicted land cover for each subwatershed that can be brought into ArcGIS or other software. 

Shapefiles and a training point dataset are also uploaded here to make current code run. The landsat image used is too large to upload, but can be found on google earth engine. It is a landsat 8 image captured on August 29th, 2021. 
