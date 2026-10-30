Analytical note

GEOCHEMICAL CHARACTERISTICS OF THE TERRITORY ACCORDING TO CARTOGRAPHIC DATA.
Geochemical map of the nearby region of Krasnoyarsk.
Overview of the spatial distribution of chemical elements on a map.

Completed by: Krasovsky A.S., Student, ICM&M

Krasnoyarsk 2026

Abstract
The work is devoted to a review analysis of geochemical designations provided on the basis of map digitization: State Geological Map of the Russian Federation at a scale of 1:200,000. Second edition Minusinsk series. Map of Quaternary formations O-46-XXXIII (Krasnoyarsk) 1999. Digitization of the source material, construction and layout of the final map were carried out in QGIS.
QGIS (Quantum GIS) is a free, open-source, cross-platform geographic information system designed for creating, editing, visualizing and analyzing spatial data. The software supports working with various vector and raster data formats, allows you to perform spatial queries, geoprocessing, map construction and export results to common formats. QGIS is used in urban planning, ecology, land management, engineering surveys and other areas where processing and interpretation of geographic information is required
The main attention is paid to the visual distribution of the selected zones, their relative position and the possibilities of using the map for preliminary analysis of the territory. The work does not involve determining modern concentrations of chemical elements, calculating standard excesses or identifying sources of pollution, since such conclusions require additional data.

Introduction
Geochemical maps make it possible to summarize information about the distribution of chemical elements and highlight areas that require more detailed study. In digital form, it is more convenient to view such materials together with other cartographic layers, analyze symbols and prepare thematic layouts.
This work uses cartographic material from 1999. Its translation into a digital environment allows you to preserve the main content of the original map, organize thematic objects and prepare visual material for further study.
1.1 Purpose of the work

Create a digital thematic map in QGIS and perform an overview visual characterization of the spatial distribution of geochemical symbols presented on the original cartographic material.

1.2 Objectives of the work

• Study the contents and symbols of the original map.
• Prepare raster material for work in QGIS.
• Create and design thematic vector layers.
• Present geochemical symbols on the final map layout.
• Describe the visual features of the distribution of designated zones.
• State the limitations of interpretation due to the age and quality of the source material.

Source materials and limitations
The main source of information is cartographic material from 1999, presented in the form of a scanned image. Upon visual inspection, uneven scanning was noted. Such features can lead to local distortions of the geometry and affect the accuracy of georeferencing.
The project used a map underlay in QGIS to visually match features and control the overall position of the raster. In some areas, the original raster and the background are visually consistent. At the same time, comparison with external mapping services revealed discrepancies in the position of individual objects. Therefore, the map is considered as an overview material, and not as a source of exact coordinates.
The scale of the final layout and printed copy was checked by measurements on paper. This check confirms that the print scale corresponds to the layout settings, but does not in itself establish the absolute accuracy of the geographic location of the source raster.
Since the source material dates back to 1999, its content characterizes the information reflected in the cartographic source at the time of its preparation. This map cannot be used as an independent assessment of the current state of the environment. An up-to-date assessment will require up-to-date samples, laboratory analyzes and additional information on natural and anthropogenic conditions.
The map allows you to get an overview of what geochemical features were identified by the authors of the source material at the time of its compilation, and to identify areas that deserve more detailed consideration. It can serve as a basis for posing further geological and environmental questions, comparison with the geological structure, hydrography and economic development of the territory if appropriate thematic data is available.

The value of the map for exploring the territory
This description characterizes the spatial structure of cartographic information. It should not automatically be interpreted as evidence of increased concentrations of elements, contamination of a specific site, or the presence of a specific source of exposure. For such conclusions, initial analytical data and information about the geochemical survey methodology are required.
The map examines the relative position of geochemical symbols, their visual grouping, the length and configuration of the selected contours. You can note areas where signs are located compactly, areas with scattered objects, as well as areas in which different types of signs are adjacent or overlap.
Visual features of spatial distribution
When describing, one should distinguish between the presence of a geochemical designation on the map and the actual concentration of the element. The original legend contains gradations, classes or levels, they can be brought in accordance with the original.
The main thematic content of the map consists of geochemical symbols, the interpretation of which is determined by the legend.
Elements: Pb, Zn, Cd, As, Cu, Co, Cr, N, Mo, V, Mn, Ba, Sr, W, Ag, Sn, P
Natural processes and objects affecting the ecological situation: zones of erosion (areal (a), areal and linear (b), lateral (c)); layers of brown coal hidden under Quaternary sediments; areas of soil subsidence (a) and waterlogging (b).
Geochemical characteristics of the environment: average concentration level (5-8); high level (8-16); moderately hazardous pollution (16-32); scattering stripes of chemical elements (a) - low concentration (8-16), (b) - medium concentration (16-32), (c) - high concentration (>32).

Geochemical information presented on the map
The general description should give the reader an idea of what territory the map covers, what main landmarks are present on it, and in what natural and economic context the geochemical designations are considered. If the original map does not contain sufficient information about the relief, geology, or land use, these characteristics should not be inferred from the appearance of the substrate alone.
The territory under consideration is located in close proximity to the city of Krasnoyarsk and covers adjacent areas, mainly in the northern, northwestern and western directions. According to the coordinate grid, the mapped area is approximately 92°00′–93°00′ east longitude and 56°00′–56°50′ north latitude. The map is compiled on a scale of 1:400,000, which allows you to simultaneously display large settlements, transport routes, river networks and individual terrain features.
In the southeastern part of the map is the city of Krasnoyarsk. To the north and northwest of it, adjacent settlements and territories are shown, among which are Emelyanovo, Minino, Solontsy, Bugachevo, Drokino, Elovoe, Snezhnitsa, Berezovka and other settlements. Their location allows us to trace the transition from the urban area to the surrounding suburban and rural areas.
A significant part of the cartographic content is the river network. The map shows the rivers Kacha, Bugach, Elovka, Talaya, Bolshoy Arey and other watercourses. River valleys and channels are represented by linear elements, thanks to which it is possible to trace their location in relation to settlements, roads and identified geochemical areas. The presence of several watercourses makes it possible to take into account the hydrographic network when further considering the spatial distribution of geochemical objects.
The map also shows the road network connecting Krasnoyarsk with surrounding settlements. Roads pass through various parts of the territory under consideration and provide a spatial reference for the displayed objects. In addition, on a cartographic basis there are individual elements of economic development of the territory and construction sites, which are especially noticeable near Krasnoyarsk and large populated areas.
The background of the map contains information about the natural and territorial features of the area. It reveals areas of vegetation, open spaces, river valleys and other underlying elements. At the same time, the original map is not intended for a detailed description of the relief, therefore one should not draw conclusions about its altitudinal characteristics and morphology without additional topographic materials.

Geographical location and general characteristics of the area
The territory under consideration is presented on the original cartographic material of 1999. Its characteristics are based on the content of the map and its legend. The description is for a general overview only: it reflects the objects and features directly shown in the source material and is not a substitute for a contemporary field survey of the area.
Digital processing technique
Processing was performed in QGIS. The source image was prepared for display in the project, after which thematic vector objects were created corresponding to the elements of the source map. For ease of design, thematic objects, contours, guide elements and signatures were placed in separate layers.
For the final layout, the coordinate system WGS 84 / UTM zone 46N (EPSG:32646) was used. This system provides coordinates in metric units in the appropriate UTM zone, but does not eliminate possible errors inherited from the original scan and georeferencing.
The design of the final map included setting up the frame, grid and its labels, numerical scale, symbols and sheet layout. Measurements requiring high accuracy were not performed in this work.
Visual characteristics of geochemical symbols
The analysis was performed on the visual distribution of symbols transferred from the original map. The description took into account the shape and relative position of the selected contours, their grouping and proximity to other elements of cartographic content. This characteristic makes it possible to identify areas where geochemical symbols are most prominently represented and areas where they are more sparsely distributed.
Contours and shading highlighted on the map should be interpreted in accordance with the legend of the source material. If a legend associates symbols with specific chemical elements or types of anomalies, this information can be used to describe the composition of the information being mapped. The presence of a designation on a map does not in itself constitute evidence of current contamination of the territory or exceeding standards.
If groups of closely spaced anomalies are visible on the map, they can be described as visual clusters of cartographic symbols. Without data on samples, concentrations, geological structure and the methodology of the initial study, it is impossible to unambiguously associate such accumulations with a specific source of chemical elements.

Interpretation options
The prepared map can be used for initial acquaintance with the geochemical content of the source material, formulation of questions for further research and selection of areas requiring additional study. You can consider the spatial grouping of designated zones, their position relative to objects displayed on the map, and differences in the visual expression of individual areas.
For a more in-depth interpretation, additional information will be required: the original legend and explanatory text of the map, data on sampling methods, laboratory results, information on the geological structure and modern observations. If these materials are available, the digital map can be supplemented with quantitative analysis.
Work restrictions
• The source material is dated 1999 and does not automatically characterize the current state of the territory.
• The original map scan was clearly uneven, affecting geometric accuracy.
• Georeferencing and digitization are likely to contain errors.
• Visual grouping of symbols does not replace statistical analysis of chemical element concentrations.
• One map cannot reliably determine the source of anomalies, cause-and-effect relationships, or the risk level of the population.
• Precision surveying and engineering measurements are strongly discouraged.
Conclusions
The original cartographic material from 1999 was transferred to the QGIS digital environment and designed as a thematic map. The created project allows you to visually examine the relative position of geochemical symbols and prepare cartographic material for educational analysis. The visual distribution of contours can be used to preliminarily highlight areas of interest for further study. Due to scanning features and geo-referencing limitations, the map must be interpreted as a survey cartographic material. Additional data are needed to confirm the concentrations of chemical elements, determine the sources of anomalies and assess the current ecological state.
