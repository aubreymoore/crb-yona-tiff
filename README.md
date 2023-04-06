# crb-yona-tiff

This repo contains an orthomosaic, in GeoTIFF format, from a drone survey of coconut palms at Villa Del Carmen, Yona, Guam. 
The drone was piloted by Jonelle N. Sayama and Keanno Lawrence A. Fausto, members of the University of Guam Drone Corps. The orthomosaic was made by Jonelle N. Sayama using Drone Deploy. Images were taken at 400 feet above ground with the camera pointed straight down.

Many of the coconut palms in the orthomosaic show damage from coconut rhinoceros beetle, *Oryctes rhinoceros*, visible as v-shaped cuts to fronds.  

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]
Data stored in this repository are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].
You are free to use the data providing you acknowledge the [University of Guam Drone Corps](https://www.uog.edu/nasa-guam-space-grant/uog-drone-corps) Pilots in anything you publish. Something like *Thanks to University of Guam Drone Corps pilots Jonelle N. Sayama and Keanno Lawrence A. Fausto for providing drone imagery* will suffice.

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

### Some assembly required

The original GeoTIFF file is larger GitHub's recommended maximum file size (50 MB), so it was split into 40 MB chunks. Run the following command lines to download the repo and reassemble the orthomosaic GeoTIFF file.
```
# download data
git clone https://github.com/aubreymoore/crb-yona-tiff.git

# change to newly created directory
cd crb-yona-tiff

# reassemble chunks
cat Map1_Orthomosaic_export_FriMar31060700467300.tif_part_?? > Map1_Orthomosaic_export_FriMar31060700467300.tif

# delete chunks
rm Map1_Orthomosaic_export_FriMar31060700467300.tif_part_??
```

If you are using Windows, you should be able to reassemble chunks using this command line (untested):
```
type  Map1_Orthomosaic_export_FriMar31060700467300.tif_part_?? > Map1_Orthomosaic_export_FriMar31060700467300.tif  
```
