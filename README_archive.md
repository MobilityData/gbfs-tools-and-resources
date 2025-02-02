# micromobility-tools-and-resources

##### Community list of shared micromobility APIs, apps, datasets, research, and software 

Have something to add or change? Open a [pull request](https://github.com/NABSA/micromobility-tools-and-resources/pulls) or [issue](https://github.com/NABSA/micromobility-tools-and-resources/issues).

------------------------------

### Table of Contents

- [Getting started](#getting-started)
- [Community](#community)
- [Data](#data)
- [Software for Creating APIs](#software-for-creating-apis)
- [Apps](#apps)
  - [Web Apps](#web-apps)
  - [Native Apps (open source)](#native-apps-open-source)
  - [Native Apps (closed source)](#native-apps-closed-source)
- [Visualizations](#visualizations)
- [GBFS](#gbfs)
  - [GBFS Libraries](#gbfs-libraries)
  - [GBFS Analysis Tools](#gbfs-analysis-tools)
  - [GBFS Validators](#gbfs-validators)
  - [GBFS Archival Tools](#gbfs-archival-tools)
- [Other multimodal data formats](#other-multimodal-data-formats)
- [Resources](#resources)

### Getting started

If this is your first time dealing with GBFS data, you might find these links useful:

- [GBFS](https://github.com/NABSA/gbfs) - A GBFS feed is a group of json files that contains bikeshare and scootershare data, like stations and station information, available bikes, and system operating information. GBFS provides real-time or semi-real-time data about the status of a micromobility sharing system.

### Community

Places to ask questions and find other community resources.

### Data

Places to access collections of GBFS and other transit and multimodal data

#### 3rd party GBFS URL directories
- [Bike Share Research](https://bikeshare-research.org) - Bike Share Research (BSR) aims to facilitate the curatation of BSS data through a collaborative and open data platform while making it API accessible.

#### Archived bikeshare data
- [Open Mobility Foundation Mobility Data Management State of Practice - Public Data Sharing](https://github.com/openmobilityfoundation/privacy-committee/blob/main/products/state-of-the-practice.md) - A list of open / public mobility data sets, and information about approaches to anonymization published by cities.

#### Proprietary (non-standard) vendor APIs
- [Bestmap shared mobility](https://bestmap.net/api_bikes) - Realtime shared mobility API that makes it easy to implement updatable data of mobility services like bikes, scooters, mopeds around the world to your software solution.
- [CityBikes](http://api.citybik.es) - REST API for aggregated bikeshare data from around the world. Powered by [pyBikes](https://github.com/eskerda/pybikes).
- [fluctuo Data Flow](https://fluctuo.com/data-flow/) - Realtime vehicles location API. Exhaustive and reliable standardized data on free-floating mobility services (bikes, kick-scooters & motor-scooters) available on real-time.

### Software for Creating APIs

Software that you can set up to provide an API to multimodal data.

- [OneBusAway](http://onebusaway.org/) - A Java app that consumes GTFS and GTFS-Realtime (along with [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)) and turns them into an easy to use [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [OpenTripPlanner](http://www.opentripplanner.org/) - An open source platform for multi-modal and multi-agency journey planning, as well as returning information about a multi-modal graph (using data sources such as GTFS and [OpenStreetMap](http://www.openstreetmap.org/)).
- [pyBikes](https://github.com/eskerda/pybikes) - Software powering [CityBikes](http://api.citybik.es) for worldwide bikeshare system info
- [mapintelligenceagency/gbfsQL](https://github.com/mapintelligenceagency/gbfsQL) - Wraps any number of GBFS feeds into an easily consumable GraphQL API. Merges relevant feeds and supports real-time updates for clients via Websockets/GraphQL Subscriptions. 

### Apps

Apps people use when traveling using shared micromobility.

#### Web Apps

- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) - A Google Web Toolkit-based web interface for OpenTripPlanner
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) - A Javascript-based client for OpenTripPlanner. No longer under development but contains links to replacement tools.
- [Bikeshare Map](http://bikes.oobrien.com/) - Status of all worldwide bikeshare stations
- [CityMapper Webapp](https://citymapper.com/nyc) - Really polished webapp with trip planner and route status for over 30 of cities.
- [thin-GBFS](https://thin-gbfs.appspot.com/) - 'A thin and low-network-use mobile web app for many common bike sharing systems.'
- [HumbleBike](https://humble.bike) - 'Simple, no frills, low-resource UI for finding CitiBikes.'


#### Native Apps (open source)

- OneBusAway Apps - [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-iphone), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), Windows 8 [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) - An Android app for [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) - An iOS app for [OpenTripPlanner](http://www.opentripplanner.org/)
- [findmybikes](https://play.google.com/store/apps/details?id=com.ludoscity.findmybikes) - An android app for trip planning and automatic recording [*(source code)*](https://github.com/f8full/findmybikes)
- [MonTransit](https://play.google.com/store/apps/details?id=org.mtransit.android) - An Android app for public transit & bike sharing in Canada [*(source code)*](https://github.com/mtransitapps)


#### Native Apps (closed source)

- [Bestmap](https://bestmap.net)
- [Transit](http://transitapp.com/)
- [CityMapper](https://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [Tiramisu Transit](http://www.tiramisutransit.com/)
- [VeloDispo](https://www.velodispo.eu)
- [Eazy.bike](https://eazy.bike/)

### Visualizations

- [GBFS-Viewer](https://github.com/idoco/gbfs-viewer) - [View micromobility data](https://idoco.github.io/gbfs-viewer/#) in your browser.
- [BikeDashboard](https://github.com/andmos/BikeDashboard) - "Simple website to track my closest Bikeshare station"

### GBFS
- [GBFS Spec](https://github.com/NABSA/gbfs) - Specification for the General Bikeshare Feed Specification, or GBFS.
- [MobilityData's GBFS Resource Center](https://gbfs.mobilitydata.org/) - information about the GBFS specification, proposed changes, resources & training, & more.
- [NABSA's Open Data Resources](https://nabsa.net/opendata/) - NABSA's GBFS and Data Principles webpage.

#### GBFS Libraries
- [BikeshareClient](https://github.com/andmos/BikeshareClient) - dotnet client for General Bikeshare Feed Specification (GBFS) written in C#. Enables dotnet developers to create apps and services using data from GBFS Bikeshare systems.

#### GBFS Analysis Tools
- [gbfs R package](https://github.com/simonpcouch/gbfs) - Functions to interface with GBFS feeds in R, allowing users to save and accumulate tidy .rds datasets for specified cities/bikeshare programs.

#### GBFS Schema
- [gbfs-json-schema](https://github.com/MobilityData/gbfs-json-schema) - JSON schemas for all existing versions of GBFS (including up to v2.2 and v3.0RC).

#### GBFS Validators
- [gbfs-validator](https://github.com/PierrickP/gbfs-validator) - [3rd party tool](https://gbfs-validator.netlify.com/) to validate GBFS feeds.

#### GBFS Archival Tools
- [bicidata](https://github.com/bicidata/bicidata) - A framework to snapshot, archive, report, and publish GBFS data.
- [A Python and StreamSets dataflow for GBFS](https://github.com/omnisci/gbfs_kafka) - The intent of this repository is to demonstrate how to create a fully open-source streaming data example using OmniSci.

### Other multimodal data formats
- [GTFS](https://github.com/google/transit/tree/master/gtfs) -  A GTFS feed is a group of text files that contains infrequently changing transit data, like stops, routes, trips, and other schedule data. Transit agencies typically update their GTFS feed every few months.
- [GTFS-realtime](https://github.com/google/transit/tree/master/gtfs-realtime) -  GTFS Realtime consists of three binary files that contain realtime vehicle positions, realtime arrival information, and service alerts. Transit agencies typically update these files every minute.
- [GTFS-flex](https://github.com/MobilityData/gtfs-flex) - A data format that models flexible public transportation services as an extension to GTFS.
- [NeTex](http://netex-cen.eu/) - A general purpose XML format designed for the exchange of complex static transport data among distributed systems managed by the [CEN standards process](https://www.cen.eu/work/ENdev/how/Pages/default.aspx).   
- [GTFS-ride](https://github.com/ODOT-PTS/GTFS-ride) - An open, fixed-route transit ridership data standard developed through a partnership between the Oregon Department of Transportation and Oregon State University.
- [Managed and Tolled Lanes Feed Specification (MTLFS)](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) - Proposal for a schema that comprise the Managed and Tolled Lanes Tolling Feed Specification (MTLFS) and defines the fields used in all of those files developed by [Santa Clara Valley Transportation Authority](http://www.vta.org/).
- [GTFS-plus](https://github.com/osplanning-data-standards/GTFS-PLUS) - A GTFS-based transit network format for *vehicle and capacity data* suitable for dynamic transit modeling developed by Puget Sound Regional Council, UrbanLabs LLC, LMZ LLC, and San Francisco County Transportation Authority.
- [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) - A GTFS-based travel demand data format focusing on individual passenger *demand* suitable for dynamic network modeling developed by San Francisco County Transportation Authority, LMZ LLC, and UrbanLabs LLC.
- [Dyno-Path](https://github.com/osplanning-data-standards/dyno-path) - (Under development - see [this post](https://github.com/osplanning-data-standards/GTFS-PLUS/pull/52#issuecomment-331231000)) Data for individual passenger *trajectories*.
- [GTFS-stat](https://github.com/osplanning-data-standards/GTFS-STAT) - An extension to a GTFS transit network with additional files that contain performance data developed by UrbanLabs LLC and San Francisco County Transportation Authority.
- [TIDES project](https://groups.google.com/forum/#!forum/tidesproject) -  Transit ITS Data Exchange Specification (TIDES) is a proposed effort to create standard data structures, APIs, and data management tools for historical transit ITS data including AVL, APC and AFC Data.
- [SAE Shared and Digital Mobility Committee](http://articles.sae.org/15799/) - Appears to be working on a data standard for car share and transportation network companies (TNCs) / rideshare.
- [Mobility Data Specification (MDS)](https://github.com/openmobilityfoundation/mobility-data-specification) - A project of the Open Mobility Foundation (OMF), MDS is a set of open source Application Programming Interfaces (APIs) focused on dockless e-scooters, bicycles, mopeds and carshare. Inspired by projects like GTFS and GBFS, the goals of MDS are to provide a standardized way for municipalities or other regulatory agencies to regulate operators and enforce policy, and ingest, compare and analyze data from mobility service providers, and to give municipalities the ability to express regulation in machine-readable formats. 
- [Alliance for Parking Data Standards (APDS)](https://www.allianceforparkingdatastandards.org/) - Formed by the [International Parking Institute (IPI)](https://www.parking.org/), the [British Parking Association (BPA)](http://www.britishparking.co.uk/), and the [European Parking Association (EPA)](http://www.europeanparking.eu/), APDS is a not-for-profit organization with the mission to develop, promote, manage, and maintain a uniform global standard that will allow organizations to share parking data across platforms worldwide.  APDS Version 1.0 documents are [here](https://www.allianceforparkingdatastandards.org/resources).
- [Mobility as a Service API](http://maas-api.org/) - A set of open documents and test suite that defines a MaaS-compatible API (e.g., a [MaaS Transport Service Provider Booking API](https://github.com/maasglobal/maas-tsp-api/blob/master/specs/Booking.md)).
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120) - The objective of this research is to develop technical specifications for transactional data for entities involved in the provision of demand-responsive transportation.  Expected completion date is late 2018.
- [NCHRP 08-119 Developing Data Standards and Guidance for Transportation Planning and Traffic Operations - Phase 1 (Anticipated)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4543) - The objective of this research is to develop standards and/or guidance to be used and adopted by the transportation community in collecting, managing, and sharing static and real-time data for transportation planning and operations.
- [General Travel Network Specification](https://zephyrtransport.org/trb17projects/7-general-travel-network-specification/) - A planned data specification for sharing travel demand model networks.
- [CurbLR](https://github.com/curblr/curblr-spec) - CurbLR is a data standard for describing curb regulations. It exists to help government effectively manage and regulate the curb and to support public and private users of city streets.
- [shared-row](https://github.com/d-wasserman/shared-row) - This is an open data specification for describing the right-of-way (ROW) for a SharedStreets Reference. It is intended to establish a common set of attributes (schema) to describe how space is allocated along a streets right of way from sidewalk edge to sidewalk edge.

### Resources

On-line courses, blog posts, and reports related to open micromobility data.

#### On-line courses

#### Blog posts

#### Academic papers

#### Government reports

#### Community-maintained lists

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Luqmaan Dawoodjee](https://github.com/luqmaan) and the [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/) have waived all copyright and related or neighboring rights to this work.
