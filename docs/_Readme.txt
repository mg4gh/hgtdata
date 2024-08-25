**********************************************************************************
*        DIGITAL LiDAR TERRAIN MODELS OF EUROPE, 1 arcsecond, Version 24         *
**********************************************************************************

THIS IS A COLLECTIVE DOWNLOAD OF ALL .HGT FILES OF AVAILABLE EUROPEAN COUNTRIES.


* Compiled and resampled by Sonny
* Website: https://sonny.4lima.de
* Twitter: https://twitter.com/SonnyLidarDTMs
* Alternatively you can also find Terrain models of the individual countries or with other Grid spaces from the Website.

=============================================================================================


Attention: Some countries are partially based on satellite-based SRTM sourcedata so far. Because there's no OpenData LiDAR-source data available yet. You can find detailed Infos in the files "_Sources.png" and "_Datasources.txt", as well as in the "_Readme.txt" file of the individual countries DTM-downloads.

=============================================================================================


This Digital Elevation Model (exactly: Digital Terrain Model DTM - in contrast to Digital surface model DSM) is based on precise LiDAR elevation sources. They have been surveyed using the method of Airborne Laserscan (ALS). The accuracy and resolution of my models' elevations compared to satellite-based surveys like ASTER, ALOS, COPERNICUS or SRTM is significantly better. Especially in wooded areas, steep rocky terrain or narrow valleys.

The areas outside of a country's source data are filled with the best available Opensource elevation data of the particular region. Either these are based on LiDAR data too. Or otherwise from the SRTM-Mission https://en.wikipedia.org/wiki/Shuttle_Radar_Topography_Mission (SRTM Version 3.0 Global 1" DTMs, Download: https://dwtkns.com/srtm30m/ ) or also from Viewfinder Panoramas by Jonathan de Ferranti (1" DTMs, http://viewfinderpanoramas.org/dem3.html ). The source files have been aranged next and above each other and resampled with a sample spacing of 1" (1 arcseconds = 1/3600 degree, equals about 20 x 30 meters) or 3" (3 arcseconds = 3/3600 degree, equals about 60 x 90 meters).

I used the worldwide popular file format of the SRTM datasets (.hgt files). Each elevation file (.hgt) represends exactly 1 x 1°, which could automatically derived from the filename. The filename specifies the southwest corner, e.g. "N47E014.hgt" represends an area from N47° to N48° latitude and E14° to E15° longitude.


PROJECTION and FILEFORMAT
*************************

- Coordinate Reference System: EPSG:4326 
- Geodetic date: WGS 84
- Coordinate system: geographic degrees
- 1 file contains 3601 x 3601 (1" model) or 1201 x 1201 (3" model) elevation pixels
- Horizontal resolution: 1 arcsecond = 1/3600 degree = 0.000277778 degree (1" model) or 3 arcseconds = 3/3600 degree = 0.000833333 degree (3" model)
- Vertical datum: Unmodified elevation system of the source data. Usually the national elevation system, based on Height above mean sea level
- Vertical resolution: 1 meter
- Byteorder: Motorola (Big Endian = most significant byte first)
- Filesize of one file: 25934402 Bytes (1" model) or 2884802 Bytes (3" model)


VERSIONS
********

v10 (2021-01-21): France v2: Use of new Lidar source data, since RGE ALTI is OpenData now
v11 (2021-02-12): Iceland v1: Initial Release
v12 (2021-02-22): Sweden v2: Use of new Lidar source data
v13 (2021-03-04): Switzerland v2: Use of new Lidar source data, since swissALTI3D is OpenData now
v14 (2021-03-17): Germany v1: Initial Release for the whole country and intergrated new Lidar data of Sachsen-Anhalt.
                  Slovakia v1: Initial Release
v15 (2021-04-09): Austria v2: Use of latest LiDAR data
v16 (2022-12-25): Iceland v2: Lots of elevation artefacts within the source data got removed
v17 (2023-01-27): Germany v2: Added LiDAR source of Hessen and finer LiDAR source of Bayern. Significantly improved quality of Baden-Württemberg, Saarland, Niedersachsen, Bremen, Schleswig-Holstein, Mecklenburg-Vorpommern
                  Luxembourg v2: Use of finer LiDAR source data
v18 (2023-04-14): Norway: Initial Releases of Svalbard v1 and Jan Mayen v1. Updated Mainland v2 with Finer data in a lot of regions due to latest Lidar Source
                  Denmark: Initial Release of Faroes v1
                  United Kingdom v2: Use of latest LiDAR-source data of England, Wales, Scotland, Isle of Man
                  Ireland v1: Initial Release
                  Portugal: Initial Releases of Mainland v0, Madeira v1, Azores v1
v19 (2023-04-19): Poland v1: Initial Release
v20 (2023-05-23): Czechia v1: Initial Release
                  Hungary v1: Initial Release
                  Lithuania v1: Initial Release
                  France v3: Use of latest source data of RGE ALTI
v21 (2023-06-16): Romania v1: Initial Release
                  Croatia v1: Initial Release
                  Italy v2: Improved Emilia-Romagna & Sardegna, using Tinitaly DEM instead of SRTM in regions without own DTM
v22 (2023-07-03): Slovakia v2: Complete coverage with LiDAR data
                  Czechia v2: Complete coverage with LiDAR data
v23 (2024-04-02): Cyprus v1: Initial Release
v24 (2024-07-16): Germany: Added LiDAR sources of Baden-Württemberg, Saarland, Niedersachsen, Mecklenburg-Vorpommern, Bremen and finer LiDAR-data of Rheinland-Pfalz
                  

SOURCES und LICENCE
*******************

This Terrain Model is OPEN, FREE and WITHOUT CHARGE. But it is licensed using the following LICENCE: Creative Commons Attribution 4.0 (CC BY 4.0),
look at https://creativecommons.org/licenses/by/4.0/deed.en

You are allowed to copy, redistribute the material in any medium or format as well as remix, transform, and build upon the material for any purpose, even commercially. Please mention my name (Sonny) and my Website (see at the top), thank you!


I exclusively used FREE Opendata sources.
The used source data is listed in detail within the file "_Datasources.txt"
