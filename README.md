# crb-yona-tiff

This repo contains an orthomosaic, in GeoTIFF format, from a drone survey of coconut palms at Villa Del Carmen, Yona, Guam. 
The drone was piloted by Jonelle N. Sayama and Keanno Lawrence A. Fausto, members of the University of Guam Drone Corps. The orthomosaic was made by Jonelle N. Sayama using Drone Deploy. 

Data stored in this repo are provided for noncommercial used under a license. 

### Some assembly required

The original GeoTIFF file is larger GitHub's recommended maximum file size (50 MB), so it was split into 40 MB chunks. These chunks can be assembled into the original file using the following command. 

```
cat Map1_Orthomosaic_export_FriMar31060700467300.tif_part_?? > Map1_Orthomosaic_export_FriMar31060700467300.tif
```


