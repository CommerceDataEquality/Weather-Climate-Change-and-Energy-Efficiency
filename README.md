# Weather-Climate-Change-and-Energy-Efficiency-Data-sets

Multi Radar/Multi Sensor System (MRMS)

The MRMS system was developed to produce severe weather and precipitation products for improved decision-making capability to improve severe weather forecasts and warnings, hydrology, aviation, and numerical weather prediction.

MRMS is a system with automated algorithms that quickly and intelligently integrate data streams from multiple radars, surface and upper air observations, lightning detection systems, and satellite and forecast models. Numerous two-dimensional multiple-sensor products offer assistance for hail, wind, tornado, quantitative precipitation estimation forecasts, convection, icing, and turbulence diagnosis.
The data sets are available via a real-time LDM feed or HTTP access at http://mrms.ncep.noaa.gov/data/. For an LDM feed contact the IDP On-boarding Team at ncep.list.idp_support@noaa.gov. For other IDP applications, contact the On-boarding Team for direct access to the data on the shared disk volume. Further descriptions are found at http://www.nssl.noaa.gov/projects/mrms/

Meterological Data Ingest System (MADIS)
MADIS is a meteorological observational database and data delivery system that provides observations that cover the globe. MADIS ingests data from NOAA data sources and non-NOAA providers, decodes the data then encodes all of the observational data into a common format with uniform observational units and time stamps. Further descriptions for the MADIS data sets may be found at https://madis.ncep.noaa.gov/.
The data sets are available via HTTP, FTP and LDM. A web form for requesting specific data may be found at https://madis-data.ncep.noaa.gov/. Users must be registered for all levels of access to the data and should contact the MADIS Helpdesk at madis-support@noaa.gov. The Helpdesk will also assist users who require FTP or LDM access to the data. For other IDP applications, contact the Helpdesk for direct access to the data on the shared disk volume. 

Model Analyses and Guidance site
The Model Analyses and Guidance (MAG) website showcases the National Weather Service’s observational database and graphical suite of numerical model analysis and guidance and provides static images of the NCEP model suite (http://mag.ncep.noaa.gov/). 

NOAA Operational Model Archive and Distribution System (NOMADS)
The NOAA Operational Model Archive and Distribution System web site (http://nomads.ncep.noaa.gov/) provides the NCEP model suite output in GRIB2 format. NOMADS provides the user with the ability to subset the model output by time, grid fields and geographic region.

NowCoast
nowCOAST v5.0 is a GIS-based online web mapping portal displaying near real-time observations, analyses, tide predictions, model guidance, watches/warnings, and forecasts for the coastal United States. Visual point-and-click access to 60 NOAA data products and services are available to users to assist in areas such as marine transportation, emergency management, search and rescue coordination, HAZMAT response, risk management, and U.S. military planning and operations via http://nowcoast.noaa.gov.

FTPPRD
This FTP service provides numerical model output in GRIB and BUFR formats. Some observational data (surface, upper air, radar) that is used as input to the models is also available. The FTP site may be found at http://ftpprd.ncep.noaa.gov/. 

WEATHER.GOV
The main web site for the National Weather Service is http://www.weather.gov/. This site provides national maps of watches, warnings and observations. Users also have access to web sites for each Weather Forecast Office, where local radar imagery and local forecasts may be found.

Datastreme
The DataStreme application converts raw meteorological data into GIF-based imagery and text products that are provided to the American Meteorological Society (AMS) for use in their K-12 teacher-enhancement course in meteorology.   While NCO has supported this application since 2005, Datastreme is now running on a 24x7 operationally supported system.  (http://www.ametsoc.org/amsedu/dstreme/)

National Water Center Website
In collaboration with the National Water Center, the NWC official website is hosted and supported by NCEP Central Operations on NOAA’s IDP systems. (http://water.noaa.gov/)

NOS CHART TILE SERVICE
In collaboration with the National Ocean Service (NOS), Marine Charts Division's (MCD), the existing Navigational Chart Data (ENCD) website is hosted and supported by NCEP Central Operations on NOAA’s IDP systems.  (http://www.charts.noaa.gov/) 

HIMAWARI Processing
The Advanced Himawari Imager (AHI) Processing application is operational and supported on the IDP.   The AHI retrieves Himawari-8 satellite data from JMA via NESDIS STAR and converts the data to tiles in netCDF4 for use in AWIPS.

National Tsunami Warning Center Website
In collaboration with NTWC, the National Tsunami Warning Center’s official website is hosted and supported by NCEP Central Operations on NOAA’s IDP systems. (http://wcatwc.arh.noaa.gov/)

#Integrated Real-time Impact Services (IRIS) and iNWS, including
HazCollect Extended(HCE)
IRIS (Integrated Real-time Impact Services) provides an integrated framework which supports contact, impact, storm report, and observation management functions. IRIS stores decoded National Weather Service text products, allowing them to be used by other services it supports, including iNWS. IRIS provides a web interface for National Weather Service ​personnel to manage impact ("Impacts Catalog"), contact, and storm report data; it provides a situational awareness mapping display; it provides a real time observation monitor; it allows the logging of communications with core partners; and it allows storm report data to be formatted into Local Storm Report and Public Information Statements and transmitted to the public. iNWS uses the decoded NWS text products in IRIS and AHPS shapefiles from the AHPS program, to generate email and SMS alerts for the emergency management, public safety, and government community of users, based on their specific needs as to what type of alerts to receive and locations for which they want to receive alerts.

HazCollect Extended: Wireless Emergency Alerts (WEA) are 90-character emergency messages sent by alerting authorities through the Federal Emergency Management Agency’s (FEMA) Integrated Public Alert and Warning System (IPAWS) to cell phones via commercial wireless carriers. NWS began participating in WEA in late June 2012. NWS activates WEA for Tsunami, Tornado, Flash Flood, Hurricane/Typhoon, Dust Storm, and Extreme Wind Warnings. NWS activation of WEA has been credited with saving hundreds of lives, particularly during tornadoes. HazCollect Extended (HCE) sends these products from the NWS to the FEMA system. HCE is one of the applications migrated from the Telecommunications Gateway servers to the IDP servers. Since HCE uses the IRIS database and IRIS coding framework, it has been integrated into IRIS and is no longer a separate application.

NWS Southern Region GIS Services
NWS Southern Region GIS services are now running and being hosted on the IDP infrastructure with newer webmapping software and an open source database.  The new geospatial web services provide users with both time-enabled services and OGC Web Mapping Services (WMS). The data can be access at http://idpgis.ncep.noaa.gov  Additionally, the new geospatial web services provide users with both time-enabled services and OGC Web Mapping Services (WMS).

Components of the National Weather Service Telecommunications Gateway (NWSTG):
BUFR Migration Tool
The BMT transforms the legacy coded text products, such as Synop and Radiosonde observations, into the BUFR binary format for dissemination to worldwide partners. 

FTPPUSH
The application sends WMO headed products via ftp or scp. Three partners remain active, GeoNetCast, HF Fax and FAA. The application pulls data directly from the CP IDP core switch. 

TGFTP
This server provides anonymous ftp and http services.  The server also fulfills international commitments for data distribution and most importantly the migrated application provides backup capabilities for the first time for this service. (ftp://tgftp.nws.noaa.gov/) 

National Law Enforcement Telecommunications System (NLETS)
NLETS provides NWS forecasts, warnings and reports to emergency responders, public safety and law enforcement personnel via the National Law Enforcement Telecommunications System, which is also used for such things as to issue All Points Bulletins, request Interpol information, or notify the police or fire department that a homeowner’s security system or fire alarm has been triggered. NLETS is one of the applications from the Telecommunications Gateway transition effort.

HazCollect Extended (HCE)
See IRIS above.
