# Signs of Spring: Charting Seasonal Shifts Through Urban Wildlife in Philadelphia


For this project, I was interested in exploring the relationship between seasonal temperature changes and the appearance of species commonly associated with spring in Philadelphia. In order to explore this question I turned to the urban wildlife in Philadelphia County, specifically, when commonly seen animals like Red-winged Blackbirds, Groundhogs, and American Robins begin to appear. These species are often considered informal indicators of seasonal change, mentioned in everything from Indigenous knowledge to things I have heard growing up or learned in school. I wanted to see whether I could create a data visualization that would support what people already seem to sense: that nature, not the calendar, tells us when spring has arrived.

By combining 2024 iNaturalist sightings with NOAA daily temperature data, I looked for patterns between warmer days and spikes in animal observations. I wasn’t just interested in verifying a hypothesis — I wanted to understand how our everyday experience of changing seasons might align with broader ecological rhythms. Can animals serve as signs of spring in a way that complements both science and culture?









## Methodology

To explore the relationship between temperature patterns and early spring wildlife activity, I gathered data from two sources: iNaturalist and NOAA. I requested all 2024 wildlife observation records for Philadelphia County from iNaturalist, and climate data for the same region and time period from NOAA. After downloading the datasets, I worked in Excel to clean and organize the data. The iNaturalist dataset came as a raw spreadsheet, with each row representing a single observation. However, this didn’t include daily totals. Instead, I used excel formulas to calculate the number of sightings per species per day so I could line it up directly with daily temperature data from NOAA. The NOAA dataset included only daily high and low temperatures, so I added a new column to calculate the daily average temperature. This allowed for a more direct and meaningful comparison with the wildlife activity data. After cleaning up all the data, I turned the excel sheets in CSV files and uploaded them to Flourish, a platform that allows me to create interactive visualizations. In Flourish, I messed with the settings to create four visualizations: three comparing temperatures and species sightings for Red-winged Blackbirds, American Robins, and Groundhogs, and the fourth to compare the first arrival dates between these three species. 





## Species and Temperature Patterns

---

###  Red-winged Blackbird

Red-winged Blackbirds *(Agelaius phoeniceus)* are common across much of North America, particularly in wetlands, meadows, and marshy urban edges. They are migratory in the northern part of their range but present year-round in the south.

.ve-media wc:20240525_red_winged_blackbird_major_donnelly_park_PD206287.jpg center width=85%

Image: [red winged blackbird major donnelly park](https://commons.wikimedia.org/wiki/File:20240525_red_winged_blackbird_major_donnelly_park_PD206287.jpg)

<a href="https://commons.wikimedia.org/wiki/File:20240525_red_winged_blackbird_major_donnelly_park_PD206287.jpg">Paul Danese</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>, via Wikimedia Commons


<div class="flourish-embed flourish-chart" data-src="visualisation/22938074"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/22938074/thumbnail" width="100%" alt="chart visualization" /></noscript></div>

In this graph, you can see Red-winged Blackbird sightings begin to rise steadily in March with the first observation recorded in Philadelphia County on March 19th, closely following the seasonal increase in average temperature.  We can see as temperatures begin increasing through March and into April, the number of Red-winged Blackbirds steadily rises, suggesting a strong positive correlation between these two variables. 

---

###  Groundhog 

Groundhogs *(Marmota monax)*, also known as woodchucks, are found throughout the eastern and central United States, often in grassy fields, forest edges, and urban green spaces. They hibernate through winter and re-emerge in the Spring when the ground begins to thaw.


.ve-media wc:Marmota_monax_por_Rodrigo_Tetsuo_Argenton_06.jpg center width=85%

Image: [Marmota monax por Rodrigo Tetsuo Argenton 06](https://commons.wikimedia.org/wiki/File:Marmota_monax_por_Rodrigo_Tetsuo_Argenton_06.jpg)

<a href="https://commons.wikimedia.org/wiki/File:Marmota_monax_por_Rodrigo_Tetsuo_Argenton_06.jpg">Rodrigo.Argenton</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>, via Wikimedia Commons


<div class="flourish-embed flourish-chart" data-src="visualisation/22939766"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/22939766/thumbnail" width="100%" alt="chart visualization" /></noscript></div>

In this graph we can observe that the first groundhog sighting in Philadelphia County occurred on April 7th, slightly after the increase of temperatures in March. While there are less observations of groundhogs to provide a more substantial trend, this still suggests that there is a correlation in the  increase in temperatures and groundhog sightings over a similar range of dates.

---

### American Robin


American Robins *(Turdus migratorius)* are widespread across the U.S. and Canada and are well-known for their adaptability to suburban and urban environments. While some overwinter in southern regions, many robins migrate north in early spring, appearing just in time for Spring.

.ve-media wc:American_robin_(71307).jpg center width=85%

Image: [American robin (71307)](https://commons.wikimedia.org/wiki/File:American_robin_(71307).jpg)

<a href="https://commons.wikimedia.org/wiki/File:American_robin_(71307).jpg">Rhododendrites</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>, via Wikimedia Commons


<div class="flourish-embed flourish-chart" data-src="visualisation/22940048"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/22940048/thumbnail" width="100%" alt="chart visualization" /></noscript></div>

In this graph, March 5th marks the first sighting of an American Robin in Philadelphia County. This graph depicts the strongest correlation between increasing temperatures and Robin sightings, with the increased temperature dates directly mirroring the increased number of Robin sightings. This pattern suggests that Robins may be one of the more reliable biological indicators for the beginning of Spring temperatures. 

---

### Comparing All Species

<div class="flourish-embed flourish-chart" data-src="visualisation/22940318"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/22940318/thumbnail" width="100%" alt="chart visualization" /></noscript></div>

This comparison chart shows that American Robins consistently appear first, with a noticeable rise in sightings beginning at the start of March. Red-winged Blackbirds follow closely behind in mid-March, and Groundhogs follow them, with the first appearance taking place in early April. This staggered return mirrors the warming pattern shown in the NOAA temperature data. You can use the toggle feature to isolate or compare species, making it easier to see how each responds to rising temperatures differently.

---

## ANALYSIS


Across cultures and scientific traditions, wildlife behavior has long been used as a sign of seasonal change. For many Indigenous communities, the return or emergence of specific animals signals shifts in the earth's cycles—knowledge built from generations of close observation and environmental relationship. In this project I have attempted to compare such culturally and ecologically meaningful patterns to local temperature data in Philadelphia, using citizen science records to ask: can animals serve as signs of spring in a way that complements both science and culture?

In the case of the American Robin (Turdus migratorius), they are considered to be the first sign of spring in several Indigenous North American traditions. It is believed that their reappearance in northern regions signals a transition in the land’s energy and a return of warmth. Scientifically, this aligns with their migratory behavior. Many robins overwinter in the southern U.S. and begin their northward movement as soon as the ground thaws and insects become available. In Philadelphia, the first robin sighting recorded in 2024 occurred on March 5th, soon after average daily temperatures began to consistently rise above freezing. Sightings increased rapidly in step with temperature, reinforcing both the cultural and ecological understanding of robins as one of the earliest indicators of spring.

Similarly, Red-winged Blackbirds (Agelaius phoeniceus) are significant in the seasonal calendars of several Indigenous groups, often associated with marshlands and wetlands coming back to life after winter. Their calls are said to signal that water is moving again and plants are beginning to grow. These birds also exhibit similar migration patterns to Robins and tend to return to breeding sites as temperatures increase. In the Philadelphia dataset, their first sighting occurred on March 19th, with numbers rising steadily into April and May. This pattern aligns with the indigenous culture’s framing of blackbirds as part of spring’s soundscape and the ecological explanation of their return to wetland territories as ice melts and insects reappear.

Groundhogs (Marmota monax), or woodchucks, are perhaps the most publicly recognized seasonal forecasters in the U.S., thanks to the tradition of Groundhog Day and figures like Punxsutawney Phil. But this cultural practice has deeper roots. Among Indigenous communities in the northeast, groundhogs are seen as timekeepers whose hibernation cycle is linked closely to the health of the land. Emerging too early could signal climate confusion; emerging late might mean the ground is still too cold or unstable. In this dataset, the first 2024 sighting was on April 7th—later than the birds and after several weeks of warming temperatures. While the number of observations is lower, this fits what science knows about their hibernation biology: they emerge only when the ground has thawed enough to support the growth of plants that they use as their food source.

However, it’s important to note that this data, while compelling, reflects not just ecological patterns but human behavior. Citizen science platforms like iNaturalist rely on people being in the right place at the right time to log what they see. That means the dataset may be incomplete or biased and that certain areas, times of day, or species may be underreported. The trends observed here align with scientific and traditional expectations, but they should be seen as suggestive rather than concrete facts.


---

## Bibliography
[Flourish](https://public.flourish.studio/visualisation/22938074/ )

[iNat](https://www.inaturalist.org/observations/export?flow_task_id=563608 )

[NOAA](https://www.ncei.noaa.gov/cdo-web/confirmation)

[Wikimedia Commons](https://commons.wikimedia.org/wiki/File:20240525_red_winged_blackbird_major_donnelly_park_PD206287.jpg)

[Audubon – American Robin](https://www.audubon.org/field-guide/bird/american-robin)

[Audubon – Red-winged Blackbird](https://www.audubon.org/field-guide/bird/red-winged-blackbird)

[National Wildlife Federation – Groundhog](https://blog.nwf.org/2011/01/10-things-you-may-not-know-about-groundhogs/)

[U.S. Forest Service – Phenology and Indigenous Knowledge](https://www.fs.usda.gov/inside-fs/delivering-mission/sustain/phenology-and-indigenous-knowledge)

[The history of Groundhog Day is more complex than you may think – The Hill](https://thehill.com/changing-america/enrichment/arts-culture/3840820-the-history-of-groundhog-day-is-more-complex-than-you-may-think/)


---

