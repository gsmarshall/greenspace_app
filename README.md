# Exploring the nuance behind Tree Equity Score
## Sam Marshall

Earth Engine App: [The Nuance and Complexity Behind Tree Equit Score]()

This Earth Engine App was created as an offshoot of an [earlier effort](https://github.com/gsmarshall/urban_greenspace) to reproduce the Tree Equity Score analysis of urban tree cover in New England. [Tree Equity Score](https://treeequityscore.org/) is a project created by the nonprofit American Forests that aims to determine the relative need for tree planting in each neighborhood in every city in the U.S. It has many strengths, but generally lacks nuance. This app examines the complex relationships between four of the components of Tree Equity Score (canopy cover, land surface temperature, nonwhite population, and low income population) in New York City, seeking to show the ways in which different on-the-ground realities could be represented as the same by the analysis.

Tree Equity Score quantifies the equity of green space distribution using a multi-criteria analysis that incorporates tree canopy cover, demographic and socioeconomic data from the U.S. Census, health survey data from the CDC, and temperature data from the USGS. It is constructed by setting a canopy cover goal for each block group, calculating how the existing canopy cover compares to this goal, and then determining how much of a priority tree planting in that block group is based on its demographic makeup, economic makeup, and temperature. Existing scientific literature suggests that the factors that go into the priority score can be correlated with each other, and in recent years journalism from publications like the New York Times has put a spotlight on the ways that tree cover is related to race, income, urban heat, and the historical inequities that influence the distribution of those phenomena. The construction of Tree Equity Score is interesting as a multi-criteria analysis because the possible correlations between its components are seemingly an intentional part of its design: by including several potentially correlated variables in one metric it seeks to represent the ways that racism and income inequality can create compounding impacts on urban tree cover and the lives of the people that live in cities. 

However, by collapsing the distribution of urban trees down to a single number this approach obscures many of the complex relationships between its component parts as well as the nuanced ways in which those components are linked with social and environmental equity. Although the popular media narrative highlights strong associations between the racial and economic composition, tree cover, and temperature patterns of different city neighborhoods, recent geographic literature suggests that the strength and direction of these relationships can vary widely between cities, between parts of cities, and when examined with different units of analysis. This app aims to examine Tree Equity Score with this literature in mind by visualizing the individual relationships between race, income, tree cover, and temperature, with the goal of highlighting how complex and geographically specific the issue of urban tree cover and its connection to environmental justice is. It is not indended to discount the usefulness of Tree Equity Score, only to spotlight how important local knowledge and careful planning are to creating a more just and equitable urban landscape.

I relied on academic literature in geography and urban studies to frame the central question and inform how I used the data and maps I was making to interrogate it. For example, reading about how different racial or ethnic groups can experience different types of inequitable access to tree cover prompted me to look at what was hiding underneath the monolithic statistical category of 'nonwhite', and reading how different studies quantified the benefits of different types of green space in different ways prompted me to think about how concentrated vs distributed tree cover might be represented the same way by Tree Equity Score but would feel very different on the ground. In creating the narrative of the app I looked for interesting spatial patterns in the data that were representative of interesting geographic stories as portrayed in the news. In doing this reading, much of what I found underscored the importance of past urban planning practices on the current character of environmental justice in cities.

Finally, I would like to acknowledge the limits of my perspective on these issues and these places: I am relying on generalized data, news media, and internet research for most of the content of this app, so it lacks the credibility and richness that can come from personal experience. The narrative of the app is intended to be observational rather than prescriptive and is intended to highlight the importance of such personal experience to addressing environmental justice issues.




Reading list/Bibliography:

“A (Not So) Brief History of Red Hook,” September 10, 2019. https://www.bklynlibrary.org/blog/2019/09/10/not-so-brief-history-red.

Bigsby, Kevin M., Melissa R. McHale, and George R. Hess. “Urban Morphology Drives the Homogenization of Tree Cover in Baltimore, MD, and Raleigh, NC.” Ecosystems 17, no. 2 (March 1, 2014): 212–27. https://doi.org/10.1007/s10021-013-9718-4.

“Borough Park, Brooklyn - The New York Times.” Accessed February 4, 2022. https://www.nytimes.com/2010/10/10/realestate/10living.html.

“Cobble Hill, Brooklyn: A Village-Like Vibe With Towering Prices - The New York Times.” Accessed February 4, 2022. https://www.nytimes.com/2020/02/19/realestate/cobble-hill-brooklyn-a-village-like-vibe-with-towering-prices.html.

Ermida, Sofia L., Patrícia Soares, Vasco Mantas, Frank-M. Göttsche, and Isabel F. Trigo. “Google Earth Engine Open-Source Code for Land Surface Temperature Estimation from the Landsat Series.” Remote Sensing 12, no. 9 (January 2020): 1471. https://doi.org/10.3390/rs12091471.

Gerrish, Ed, and Shannon Lea Watkins. “The Relationship between Urban Forests and Income: A Meta-Analysis.” Landscape and Urban Planning 170 (February 1, 2018): 293–308. https://doi.org/10.1016/j.landurbplan.2017.09.005.

Grove, J. Morgan, Dexter H. Locke, and Jarlath P. M. O’Neil-Dunne. “An Ecology of Prestige in New York City: Examining the Relationships Among Population Density, Socio-Economic Status, Group Identity, and Residential Canopy Cover.” Environmental Management 54, no. 3 (September 2014): 402–19. https://doi.org/10.1007/s00267-014-0310-2.

Kensinger, Nathan. “As Red Hook’s Industrial History Is Demolished, What Comes next for the Neighborhood?” Curbed NY, June 27, 2019. https://ny.curbed.com/2019/6/27/18761177/brooklyn-red-hook-industrial-history-preservation-photo-essay.

“Languages of New York City.” Accessed February 4, 2022. https://languagemap.nyc/.

Leahy, Ian, and Yaryna Serkez. “Opinion | Since When Have Trees Existed Only for Rich Americans?” The New York Times, June 30, 2021, sec. Opinion. https://www.nytimes.com/interactive/2021/06/30/opinion/environmental-inequity-trees-critical-infrastructure.html.

Lees, Loretta. “Super-Gentrification: The Case of Brooklyn Heights, New York City.” Urban Studies 40, no. 12 (November 2003): 2487–2509. https://doi.org/10.1080/0042098032000136174.

Leland, John. “Why an East Harlem Street Is 31 Degrees Hotter Than Central Park West.” The New York Times, August 20, 2021, sec. New York. https://www.nytimes.com/2021/08/20/nyregion/climate-inequality-nyc.html.

Lin, Jian, Qiang Wang, and Xiaojiang Li. “Socioeconomic and Spatial Inequalities of Street Tree Abundance, Species Diversity, and Size Structure in New York City.” Landscape and Urban Planning 206 (February 1, 2021): 103992. https://doi.org/10.1016/j.landurbplan.2020.103992.

Locke, Dexter H., Billy Hall, J. Morgan Grove, Steward T. A. Pickett, Laura A. Ogden, Carissa Aoki, Christopher G. Boone, and Jarlath P. M. O’Neil-Dunne. “Residential Housing Segregation and Urban Tree Canopy in 37 US Cities.” Npj Urban Sustainability 1, no. 1 (March 25, 2021): 1–9. https://doi.org/10.1038/s42949-021-00022-0.

Locke, Dexter H., Shawn M. Landry, J. Morgan Grove, and Rinku Roy Chowdhury. “What’s Scale Got to Do with It? Models for Urban Tree Canopy.” Journal of Urban Ecology 2, no. 1 (January 1, 2016): juw006. https://doi.org/10.1093/jue/juw006.

Maas, Jolanda, Robert A Verheij, Peter P Groenewegen, Sjerp de Vries, and Peter Spreeuwenberg. “Green Space, Urbanity, and Health: How Strong Is the Relation?” Journal of Epidemiology & Community Health 60, no. 7 (2006): 587–92. https://doi.org/10.1136/jech.2005.043125.

Mahler, Jonathan. “How the Coastline Became a Place to Put the Poor.” The New York Times, December 4, 2012, sec. New York. https://www.nytimes.com/2012/12/04/nyregion/how-new-york-citys-coastline-became-home-to-the-poor.html.

Rosenblum, Constance. “A Witness to Gentrification in Cobble Hill.” The New York Times, September 6, 2013, sec. Real Estate. https://www.nytimes.com/2013/09/08/realestate/a-witness-to-gentrification-in-cobble-hill.html.

Shen, Yanan, Fengyun Sun, and Yue Che. “Public Green Spaces and Human Wellbeing: Mapping the Spatial Inequity and Mismatching Status of Public Green Space in the Central City of Shanghai.” Urban Forestry & Urban Greening 27 (October 1, 2017): 59–68. https://doi.org/10.1016/j.ufug.2017.06.018.

“Urban Designer Series: Robert Moses | Smart Cities Dive.” Accessed February 4, 2022. https://www.smartcitiesdive.com/ex/sustainablecitiescollective/urban-designer-series-robert-moses/54826/.

Wolch, Jennifer R., Jason Byrne, and Joshua P. Newell. “Urban Green Space, Public Health, and Environmental Justice: The Challenge of Making Cities ‘Just Green Enough.’” Landscape and Urban Planning 125 (May 1, 2014): 234–44. https://doi.org/10.1016/j.landurbplan.2014.01.017.

Wüstemann, Henry, Dennis Kalisch, and Jens Kolbe. “Access to Urban Green Space and Environmental Inequalities in Germany.” Landscape and Urban Planning 164 (2017): 124–31. https://doi.org/10.1016/j.landurbplan.2017.04.002.

Yu, Chen, and Wong Nyuk Hien. “Thermal Benefits of City Parks.” Energy and Buildings 38, no. 2 (2006): 105–20. https://doi.org/10.1016/j.enbuild.2005.04.003.
