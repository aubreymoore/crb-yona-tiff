# crb-yona-tiff

This repo contains an orthomosaic, in GeoTIFF format, from a drone survey of coconut palms at Villa Del Carmen, Yona, Guam. 
The drone was piloted by Jonelle N. Sayama and Keanno Lawrence A. Fausto, members of the University of Guam Drone Corps. The orthomosaic was made by Jonelle N. Sayama using Drone Deploy. 

Data stored in this repo are provided for noncommercial used under a license. 

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

### Some assembly required

The original GeoTIFF file is larger GitHub's recommended maximum file size (50 MB), so it was split into 40 MB chunks. These chunks can be assembled into the original file using the following command. 

```
cat Map1_Orthomosaic_export_FriMar31060700467300.tif_part_?? > Map1_Orthomosaic_export_FriMar31060700467300.tif
```


