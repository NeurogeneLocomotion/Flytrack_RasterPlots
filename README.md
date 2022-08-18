# Flytrack_RasterPlots
Code for ploting Raster Plots


System Requirements: Windows 10 or macOS Python 3.4.6

Instalation Time: No Instalation needed

Demo: 
Input files: CSV Files with tracking for each fly with info including a column for the Frames, Seconds , x and y positions and LED intensities. (Example file in annex) Insert folder_name and file_name.

Function data_treatment select columns: frames, time, x and y coordinates, and LED_lum and transform data into np_array Returns:1) data_array containing frames, time, x and y coordinates 2) LED_lum column

Raster plot will show a representation of the behaviours performed by the fly over time. The behaviours we classify are stoping (no forward velocity no pixel change), grooming (no forward velocity, only pixel change), and walking( forward velocity and pixel change).

In the function classify_pxl_change(pxl_change, velocity) we define the parameters for classification of the different behaviours
Outputs are Raster Plot, Histogram showing the percentage of events and fraction of events, Raster plot flies order by time spent walking. 


Instructions for use: Change input folder_name and file_name and run the code.
