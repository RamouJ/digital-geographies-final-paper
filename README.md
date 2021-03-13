# Digital Geographies Final Paper

## Introduction to AEMP

The digital-geography project I will be discussing in this paper, is an interactive web map produced by the **Anti-Eviction Mapping Project**, which is a digital cartography collective documenting gentrification struggles and creating tools for resistance (Anti-Eviction Mapping Project). The project is comprised of volunteers who study and visualize racial capitalism, techno-capitalism, political economy, and tools for resistance. They are also partnered with over 30 non-profit organizations that are all working to improve race relations and equity in the United States. This web map, picture below, is titled *“Killings by Oakland PD 1968-2020”*:
![Screenshot of web map][img/dashboard.JPG]

## Web Map Description
The goal of this project is to visualize the number of documented killings by Oakland Police since 1968. The dashboard is comprised of a map, a legend, a credit box, and several summary statistics displaying the data by race and neighborhood. The map is very simplistic, only highlighting a few major streets, cities, and landmarks. It contains different colored markers with animations signifying the location of the killings, and polygons shaded based on the murder rate. The markers also display pop-ups of information about the victim when clicked on, and details about the incident when hovered over. The legend displays the key for the colors of each marker, and a scale with a color ramp for the number of neighborhoods by murder. 
![Screenshot of web map legend][img/legend.JPG]

The timeline below the map displays a bar chart for the number of killings each year since 1968 based on the number of markers present on the map, so this chart changes as you adjust the viewing window of the map.
![Screenshot of timeline on web map][img/timeline.JPG]

The final components of the dashboard are two functions that allow you to filter and view the data by race, and neighborhood. As well as a credit box that credits the authors of the software and data used to produce the map, and buttons to adjust the viewing area of the map. 
![Screenshot of filters on web map][img/filters.JPG] 
![Screenshot of credit bar on web map][img/scale_bar.JPG]

## Intended Audience
Overall, these elements of the web map allow the user to make conclusions based on mainly race and geographic location. The intended users of this map are those seeking information about police violence in Oakland, or California as a whole. High school students, college students. Politicians, and anyone who can read a map could use this project to visualize officer-involved killings in a number of ways.

## Data
The data used to produce this map is credited to OpenStreetMap, and possibly the city of San Francisco or another organization that monitors such data. The map does not include any links to a dataset or a website to view meta data. It does however, credit Stamen and Carto which are data visualization and cartography software used by the author to produce this visualization. While inspecting the map, I found that they also used leaflet tiles and functions to decorate the map. Such as the leaflet-layer, leaflet-pane, and leaflet-popup-pane to name a new. The data does not appear to be update itself so I am assuming the data used in this web map is not connected to a server that is continuously updated.

## Design Critique
First off, this web map is very responsive and easy to navigate. Whether I am in full screen or a shrunken half screen, the elements of the map adjust to fit the screen, elements collapse and reposition themselves accordingly. The base map used is provided by Stamen Design and is copyrighted. Its colors are off-white, grey, and black, with smooth lines and minimal map details. Some improvements to the design of the dashboard include enlarging the text so it’s easier to read, and emphasizing the grey-colored text against the white background. Overall, it is a very simple and uncluttered map.

## Pros and Cons
Pros
-	The dashboard is very simplistic and straight-forward
-	The filters allow the reader to derive richer insights
- The bar chart is helpful for visualizing the data overtime

Cons
- Some of the filters by race and neighborhood do not accurately reflect the number of killings in the specified category
- The animations are a bit distracting while trying to process the map
- The colors of the markers do not match the colors in the legend
- The author of the web map does not explicitly list or link to a source for the data

## Reflection
This map is reminiscent of a quote from Sarah Bond, which reads: 
> “many prominent African-American activists turned to maps and other visualizations in order to help the public--and even the president--to understand the detrimental effects of slavery on the country” (Bond).
Historically, oppressed populations like blacks in America relied on maps to determine areas that were and were not safe for them to be in. A map such as the one discussed in this paper is a prime example of what a typical black family would search for before relocating to Oakland. Not only can these maps help us visualize history, they can also help us plan future decisions using events that have taken place in history as a predictor. Gabrielle Foreman, a professor of English and Black American Studies & History at the University of Delaware, believes 

> “Digital Humanities can be used as a form of high-tech quilting that likewise stitches together disparate parts of the past” (Strong and Ryan-Mosley). 
Foreman and Bond make similar arguments in that maps are essentially stories told through geographic visualizations. For this reason, we can use them and other GIS technologies to tell stories of the past and predict events in the future. 

The Anti-Eviction Mapping Project(AEMP) mainly focuses on housing inequalities, income disparities, and exposing patterns of gentrification. They also 
> “believe in a narrative oral history and video work centers that work to rectify the displacement of people and complex social worlds, but also modes of resistance. Maintaining antiracist and feminist analyses as well as decolonial methodology, the project creates tools and disseminates data contributing to collective resistance and movement building” (Anti-Eviction Mapping Project). 
Every map the project produces is either politically, socially, or economically motivated. For example, the map I looked at addressed violence against black and brown bodies in Los Angeles’s urban ghettos at the hands of law enforcement officers. Another map I considered analyzing depicted the number of evictions in San Francisco since 1994 as a result of the Elis Act. 

![Map of Ellis evictions][img/ellis.JPG]

This map focuses on housing discrimination and gentrification of urban areas where predominantly black, brown, and poor people are exploited for their lucrative residences. The mission of the AEMP is to map these scenarios where they see trends in exclusion and dispelling of black and brown people. This is necessary because the corporations at the root of gentrification tend to produce maps of their developments that neglect to display the colonial-like efforts it took to build their construction sites. The AEMP adds, 
> “while real estate companies may distribute their maps depicting renamed and whitewashed neighborhoods, our maps hold the stories of long-time residents who hold decades of memory, including all of the old names” (Anti-Eviction Mapping Project). 
The project participants act as activists in the streets, campaigning and posting flyers to bring awareness to the problem their maps aim to visualize. 
> “While big tech advertises their private shuttle routes throughout the Bay Area, we can overlay those bus stops with the rise of market driven evictions and displacement. These maps not only counter the stories that justify the Bay Area’s elite, but they work to affirm the experiences of those whom gentrification was never meant to benefit” (Anti-Eviction Mapping Project). 
This is the essence of what makes programs like AEMP crucial in the fight for social justice, income equality, and other institutional issues that affect black, brown, and poor people in America.
 
References
- Anti-Eviction Mapping Project. AEMP Handbook by The Anti-Eviction Mapping Project (AEMP). Handbook. San Francisco, 2018.
- Bond, Sarah. "How Is Digital Mapping Changing The Way We Visualize Racism and Segregation." Forbes 20 October 2017. Website.
- Strong, Jennifer and Tate Ryan-Mosley. "The activist dismantiling racist police algorithms." MIT Technology Review 5 June 2020. Website.




