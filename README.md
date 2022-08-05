## Welcome!

My research is motivated by the drive to understand marine ecosystems more fully across scales and trophic levels. While my research is multifaceted, I am generally focused on spatial and community ecology with experience in collaborating with ecologists and oceanographers and stock assessors to foster ecosystem-based and climate ready fisheries management. My quantitative expertise ranges from distinct formulations of statistical predictive habitat models, spatial statistics as well as multivariate non-parametric statistics commonly used in community ecology. Throughout my education and professional experiences, I have led and participated in multiple marine ecological (theoretical, statistical & field) studies ranging from the nearshore to offshore marine environments (sampling larval fish assemblages to top-predator observing, tracking, surveys and censuses) in the California Current as well as abroad (e.g. in Norway and South America). I’ve worked with a wide variety of large biotic and abiotic datasets ranging from daily to composite satellite images, multi-decadal spatially explicit fishery independent survey datasets, as well as satellite tracking of multiple individual animals at a daily scale over multiple years. I use R, MATLAB (both using many associated toolboxes or packages), ArcGIS 9/10+, and GitHub among other software. Additionally, I have had training and some experience using the Stock Synthesis platform (SS3 & R4SS) as well as the Spatial Population Model (SPM) for developing spatially explicit stock assessments.

### Research topics
#### 1. Northern California Current
##### a. Time-varying epipelagic community structure
I investigated the spatial and temporal diversity and community composition of mid- to upper trophic level species in the upper water column off of Oregon and Washington (and also went out on NOAA and chartered research vessels with NOAAs Fish Ecology Division). In a study published in Frontiers in Marine Science, I used a pelagic seascape approach to understand the epipelagic fish and macro-invertebrate assemblage structure off of Oregon and Washington using remotely sensed (MODIS-Aqua ocean color and temperature data) and in-situ biological and physical measurements (CTD data). I conducted a generalized additive mixed effects model with ordination scores as the response variable and remotely and in-situ oceanographic data in order to predict spatial maps of community composition as hindcasts and forecasts of community gradients. Extensions of this analysis for management purposes could include removing, for example, certain salmonid species from the community analysis [to avoid double counting]) and relating this index as another ecosystem indicator to help predict certain salmonid species returns, as well as albacore landings for example.

![timevaryingseascapefigure](https://user-images.githubusercontent.com/62513493/182972588-73467ce4-71ac-4fa3-bf54-fd58667c3d69.jpg)

[Barceló et al. 2021 Frontiers in Marine Science](https://www.frontiersin.org/articles/10.3389/fmars.2021.586677/full)

##### b. Pelagic climate change refugia
I have also developed an approach to identify potential climate change refugia which was applied to the Northern California Current Ecosystem. Refugia are areas relatively buffered from contemporary climate change that enable the persistence of valued physical, ecological, or sociocultural resources (Keppel et al. 2012). Spatially identifying refugia is important for conservation and applied management. In this study, I analyzed data from a unique and long-term (1999–2015) standardized survey of pelagic marine and anadromous species off Oregon and Washington in the northern California Current to identify such refugia. I used quantitative approaches (variable coefficient GAMMs) to assess locations with high species richness and community persistence relative to local and basin-scale environmental fluctuations. Regions identified as potential refugia are characterized by a species-rich community with low interannual temporal community change. This region contrasts with adjacent areas to the south and offshore that have lower species richness, and higher temporal species community change. I identified areas with species compositions that are more influenced by basin-scale climatic fluctuations than others. I proposed that upwelling regions with retentive topographic features, such as wide continental shelves, can function as marine refugia for pelagic fauna, whereas offshore locations are potentially more climatically sensitive and experience high temporal change in species composition. Further identification of these marine refugia using in-situ data from pelagic or demersal ecosystems is possible and could help guide management in the face of climatically driven change. For example, a recent publication: Alabia, Molinos, Hirata, Mueter, Hirawake, & Saitoh (2021) Global Change Biology, followed a similar methodology to identify potential groundfish refugia in the Eastern Bering Sea.

![refugiafigure](https://user-images.githubusercontent.com/62513493/182974008-0d4b4666-fc4d-4675-aeef-02e68ea5a6f1.jpg)

[Barceló et al. 2018 Global Change Biology](https://onlinelibrary.wiley.com/doi/abs/10.1111/gcb.13857)

##### c. Integrating habitat, prey and predators over space and time (Torres, Barceló, et al. in prep)

In collaboration with OSU’s Marine Mammal Institute (Dr. Leigh Torres) and a broader multi-institution team, we carried out a project intended to integrate forage fish distribution models (using MODIS temperature and Chl-a and NOAA-GFDL’s ESM2M) with California sea lion survey-based observations and tracking data to describe spatial overlap and spatial shifts of predators and prey species under various environmental scenarios (i.e. average conditions, ENSO cycles, and forecasted climate change). In this study I used satellite data extracted from the NOAA’s ERDDAP using R. I also used ESM2M data layers provided by R. Rykaczweski (PIFSC-NOAA) to model potential distributional shifts and overlap of both predators and prey in the future (2 periods). This research could be extended to other predators and prey combinations in this region.

![sealionoverlapfigure](https://user-images.githubusercontent.com/62513493/182974006-2bfdf650-fcd0-4d49-a738-364fca14fc02.jpg)

#### 2. Norwegian Skagerrak Archipelago

My work on community composition and diversity also extends to the coastal zone of southeastern Norway. In this region, I’ve collaborated both in the field on the beach seine survey during two different survey years, and analyzed the extensive multispecies beach seine survey dataset that is more than a century long and spatially explicit. I used multivariate statistical techniques to characterize the change in taxonomic community composition through time, determined whether there was a biogeographic affinity change in the community (southern biogeographic affinity species replacing species with more boreal biogeographic affinities), as well as change in the species functional trait assemblage (research in development). Juvenile nursery habitats are an important and sensitive to disturbances caused by climate variability. I identified a progression of the community composition through the decades to a novel no-analog community space in the ordination. This region is impacted by the variable coastal current of the region as well as broader changes in the North Sea and adjacent areas. I have initiated a spatially explicit community analysis using an updated version of this dataset and would be keen to explore community resilience topics using this lengthy dataset with interested students and colleagues. An U.S.(Oregon) - Norway fisheries/marine ecology exchange program would be a lovely extension of this collaboration. This could possibly be developed with the University of Agder and the Institute of Marine Research at Flødevigen Marine Research Station.

![norwayordinationfigure](https://user-images.githubusercontent.com/62513493/182974005-c1844b0e-bc06-4174-8292-fdf4603aa8ee.jpg)

[Barceló et al. 2016 Global Change Biology](https://onlinelibrary.wiley.com/doi/10.1111/gcb.13047)

#### 3. California nearshore ecosystems and marine reserves
##### a. Timescales of fishery yield increase after marine reserve implementation

As a postdoctoral researcher with Drs. Louis Botsford at the University of California Davis, collaborating with Drs. Alan Hastings (UC Davis) and Dr. White at Oregon State University, we contributed to the Sustainable Fisheries and Aquaculture Goal 3 of the California Sea Grant Strategic plan by co-developing a two-patch age structured model to understand the population dynamics of nearshore coastal kelp forest species (mainly in CA) in order to propose estimated timescales of population (biomass) and fishery yield responses given the implementation of marine reserves. The results from this study suggest a multi-decade-long time until detection of rockfish species increases in fishery yield post implementation of a marine reserve. These values are derived from fishery dependent values (biomass and fishing mortality rates) and provide a guideline as to which species to monitor first to track reserve responses.

![timescalesfigure](https://user-images.githubusercontent.com/62513493/182974002-6dd9cbdc-a56d-4d15-b643-76cdf61c4d80.jpg)

[Barceló et al. 2021 ICES JMS](https://academic.oup.com/icesjms/article/78/5/1860/6282521)

##### b. Ecological and Engineering Resilience in Age Structured Populations (White et al. in review)

The UC Davis/OSU team and I also investigated the population level population resilience (engineering resilience) of these fish to environmental fluctuations and pulse disturbances. Specifically, we were interested in understanding the recovery time and the severity of the impact on species with different life histories given a pulsed reduction of recruitment of a given species. We also plotted these two aspects of the species’ response to a pulse disturbance in a bivariate framework (following an approach suggested in Ingrish & Bahn, 2018).  Additionally, we also began to investigate the ecological resilience of age structured populations with different life histories and fishery characteristics given different frequency ENSO-like disturbances, presented as an e-lightening poster at the Ocean Sciences Meeting, 2020.

![pulsedistrubancediagram](https://user-images.githubusercontent.com/62513493/182974001-e84d560b-c1ad-4e08-8daf-3f7abe4fab66.jpg)

#### 4. Global Spatial Stock Assessment Simulation Experiment (Berger, Hoyle, Barceló, Goethel et al. in prep)

Recently, I was a research associate/postdoctoral researcher with ECS Federal in support of NOAA Fisheries’ Office of Science and Technology and the NWFSC & AFSC working on a spatial stock assessment project simulating the spatial distribution and population structure of Antarctic toothfish and yellowfin tuna in order to explore critical spatial assumptions of assessment models through simulation testing and developing datasets with the Spatial Population Model (developed by Dr. A. Dunn) as the operating model.  Our objectives with this experiment are three-fold: “1) to discuss best practices in spatial model development by exploring the decision-points of each analyst. This will highlight how differences among platforms influence decisions at each stage of development of a spatial stock assessment model, provide insight into why analysts choose certain spatial functionality, and how goodness of fit is determined in a spatial context; 2) to evaluate within-platform performance and the impacts of ignoring spatial structure by comparing spatial and spatially aggregated model configurations; and 3) explore general performance across different categories of spatial models (e.g., non-spatial, spatially-implicit, spatially-stratified, and fully spatiotemporal) by comparing bias and precision across the broad model categories.” 
This experiment was led in collaboration with international colleagues at NIWA in New Zealand and collaborative with stock assessors around the world (Spain, Australia, New Zealand, USA (including Alaska, Hawaii, North Carolina), Norway, Iceland). We simulated fully spatial Indian Ocean Yellowfin tuna datasets based on fishery data from the Indian Ocean using the Spatial Population Model (SPM) and aggregated these to 4 area and panmictic aggregations using an wrapper function developed and provided by NIWA. These datasets were distributed to participants via GitHub to conduct assessments using their assessment platform of choice (SS3, CASAL2, GADGET2, MLTF-CL, SPASAM, MAS, and Cao et al.’s Spatiotemporal Model). We have planned participant webinars (Spring 2022) as a venue to report results and findings. Our plans are to synthesize these spatial assessment results across levels of aggregation and type of assessment model in order to inform the next generation of spatial stock assessment platforms. The project is currently located [here](https://aaronmberger-nwfsc.github.io/Spatial-Assessment-Modeling-Workshop/).

![spatialstockassessmentexperimentdiagram](https://user-images.githubusercontent.com/62513493/182973998-be7b9bd2-5125-40e0-aa80-40434714c3c4.jpg)

#### 5. High-use areas, seasonal movements and dive patterns of juvenile loggerhead sea turtles in the Southwestern Atlantic Ocean 

Characterizing the behaviors of sea turtles and identifying high-use areas as they vary in time and space is important for conservation planning, particularly when turtles overlap with fisheries that may unintentionally harm them. Between July 2006 and March 2010, 27 satel- lite transmitters were deployed at sea on juvenile loggerheads Caretta caretta captured as bycatch in the Uruguayan and Brazilian pelagic longline fisheries operating in the Southwestern Atlantic Ocean. Tracking duration ranged from 3 to 639 d (mean ± SD: 259 ± 159 d; n = 27), during which turtles moved between latitudes of 25 to 45° S and longitudes 35 to 54° W. High-use areas for the tracked turtles were over the continental shelf and slope within the Uruguayan, Argentin- ian, and Brazilian exclusive economic zones and in adjacent international waters. Diving informa- tion was available for 5 turtles. The maximum dive depth recorded varied between 100 and 300 m. Two turtles demonstrated potential bottom-feeding behaviors by diving to depths that corre- sponded closely with the depth of the seafloor (<200 m) at their given location. The sea surface temperature encountered by tagged turtles was on average 19.8 ± 2.3°C (range: 10.2 to 28.4°C), and turtles showed an affinity for waters supporting moderate to high primary productivity levels (0.43 ± 0.89 mg m−3 chlorophyll a). Latitudinal movements varied by season and sea surface tem- perature. These findings, along with those of other studies conducted in the region, demonstrate the need to strengthen ongoing collaborative efforts between neighboring countries and other international partnerships to further the research and management of sea turtles in this area.

![loggerheadsswa](https://user-images.githubusercontent.com/62513493/183141964-a9d5e4fd-f0e5-4245-b183-7ee69f488adc.jpg)

Other projects and publications I've contributed to can be found on [researchgate](https://www.researchgate.net/profile/Caren-Barcelo-2).
