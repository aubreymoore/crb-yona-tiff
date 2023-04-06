# crb-yona-tiff

This repo contains an orthomosaic, in GeoTIFF format, generated from drone images capturing damage to coconut palms by coconut rhinoceros beetle.

Some assembly is requred. The original TIFF is too big to comply with GitHub requirements. So it was split into 40 MB chunks. These chunks can be merged using the following command. 

```bash
cat Map1_Orthomosaic_export_FriMar31060700467300.tif_part_?? > Map1_Orthomosaic_export_FriMar31060700467300.tif
```
valid
When you are sure that the resulting GeoTIFF is valid, by opening it with QGIS or other suitable app, chunks can be removed using:

```bash
rm Map1_Orthomosaic_export_FriMar31060700467300.tif_part_??
```


