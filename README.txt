Description of a dataset corresponding to Vessel Mounted Acoustic Doppler Currrent Profiler (VM-ADCP; Teledyne RD Instruments 75 kHz Ocean Surveyor) data along hydrographic section Seal Island (SI) of the Atlantic Zone Monitoring Program since 2008. The ADCP was setup in narrow band single-ping profile mode with bottom track enabled, using an 8-m bin size, 8-m blanking distance, 3 s between ensembles, and 1.5 s between bottom and water pings. This enabled vertical profiles to be collected with a top bin between 16-40 m (dependent on vessel draft) and bottom bin as deep as 650 m. Navigation data were collected using a differential GPS and/or 3D differential GPS when possible. Single ping data with navigation referencing (with bottom-track referencing applied during GPS outages) were quality controlled to apply corrections/calibrations, remove spikes, and correct vessel heading using the CODAS3 software suite developed by the University of Hawaii. Data were then extracted from CODAS3 archives with a percent good threshold of 70 – 80%, and de-tided using tidal predictions obtained from a high-resolution 2-dimensional numerical tidal model with observational sea level datasets (WebTide).

Each of the 21 files correspond to an individual mission and contains the following columns:

1. "year"
Year of the measurement (2008-2023)

2. "mon"
Month of the measurement (1-12)

3. "day"
Day of the measurement (1-31)

4. "hr"
Hour of the measurement (0-23)

5. "min"
Minute of the measurement (0-59)

6. "sec"
Second of the measurement (0-59)

7. "deciday"
Decimal day of the measurement (0-366)

8. "distance(5Km_bin)"
Distance of the measurements since Station SI-01 along Seal Island section

9. "depth(m)"
Depth of the measurement

10. "U_Vel(cm/s)"
Eastward velocity in cm/s

11. "V_Vel(cm/s)"
Northward velocity in cm/s

12. "Latitude"
Latitude of the measurement (Decimal degrees North - XX.XX N)
53.60	304.97	-55.03	
13. "Longitude(360deg)"
Longitude of the measurement (Decimal degrees 0-359.99)

14. "Longitude"
Longitude of the measurement (Decimal degrees East - XX.XX E)

15. "U_Tide(cm/s)"
Tidal Eastward velocity in cm/s

16. "V_Tide(cm/s)"
Tidal Northward velocity in cm/s

17. "U_Vel-U_Tide(cm/s)"
De-tided Eastward velocity in cm/s

18. "V_Vel-V_Tide(cm/s)"
De-tided Northward velocity in cm/s

19. "Vol_Transport_V_Raw(m^3/s)"
Eastward Volume transport on the pixel

20. "Vol_Transport_V_Raw-V_Tide(m^3/s)"
Northward Volume transport on the pixel


--- Credit ---

The data were curated by Steve Snook at the Northwest Atlantic Fisheries Centre for the account of the Atlantic Zone Monitoring Program of Fisheries and Oceans Canada.

Further description of the data can be found in the following publication:

Lin, P., R.S. Pickart, F. Cyr, S. Snook, F. Bahr & S.J. Déry. The Labrador boundary current system and its influence on cross-shelf exchange, submitted to Journal of Physical Oceanography, October 2025.


