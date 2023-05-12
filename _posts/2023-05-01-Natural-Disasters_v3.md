---
title: Natural disasters, Climate change and Economic development
date: 2023-05-01 12:00:00 -5000
categories: [natural disasters,economic development]
tags: [matural disasters,climate change,economic development]     # TAG names should always be lowercase
authors: [Ásmundur, Ásmundur] 
---



As our planet grapples with the devastating effect of climate change, the world is witnessing an alarming 
trend: natural disasters are becoming more frequent, more devastating, and mercilessly targeting the most 
vulnerable.

{% include Incidents_interacrive_barplot_1.html %}

The delicate balance of our environment has been upset by climate change caused by human activity such as
burning fossil fuels, deforestation, and unsustainable agriculture practices. Rising temperatures, melting
glaciers, and changing weather patterns have set the stage for a surge in natural disasters. From hurricanes
and floods to droughts and heatwaves, these cataclysmic events are no longer distant bad dreams but recurring
nightmares.

[Maybe the map here and talk more about it]

This article delves into the reality that natural disasters do not discriminate. Instead, they exacerbate 
existing inequalities, hitting countries with limited economic resources the hardest. We aim to raise 
awareness of the sobering connection between economic inequality, climate change, and these calamities' 
toll on human life. 

## Disparities in Natural Disaster Impacts 

When faced with natural disasters, the impacts are often disproportionately felt. The worst hit by 
intensifying natural catastrophes are frequently those nations with less developed economies and lower 
GDP per capita. In their attempts to address the effects of climate change, these countries face a 
challenging task as they struggle with poverty, poor infrastructure, and few resources.

The scatter plot below visualizes the relationship between the magnitude of people affected by a natural 
disaster and a country's GDP per capita where the disasters occur. The plot also shows how the relationship
has developed in recent years, together with the number of inhabitants in the countries and more information.


{% include scatter_gdpc.html %}

Pre-event vulnerability and post-event response explain the difference in disaster outcomes between 
high-income and low-income groups. Natural disasters can occur and have adverse effects depending on 
various factors, including geography, personal resources, community infrastructure, and political stability. 
Additionally, social unrest may accompany poverty, especially when there are significant disparities in the 
distribution of wealth and income. Natural disasters can leave less economically developed nations in a 
downward spiral of poverty and economic hardship. Vulnerable populations are further impoverished by 
disrupted livelihoods, damaged infrastructure, and decreased agricultural productivity. The arduous path 
to recovery becomes an uphill battle, impeding economic growth and perpetuating systemic inequalities." 

In 2007, Toya and Skidmore concluded that to get a deeper understanding and to reduce disaster deaths and 
damages, income is not the only significant indicator of progress. Instead, more diverse economic and social 
indicators like increasing levels of education, openness, a robust financial sector, and a smaller 
government are also crucial. For example.

{% include income_1_of_the_second_20.html %}

In this scaterplot it is visible that the number of poeple affected by droughts and heatwaves is increasing non linearly 
in to the income the richest fifth of the popuplation 

{% include income_2_of_the_second_20v2.html %}

Also we can see that when choosing another fifth of the population  that there is a positive correlation. Therefore, the income is very significant. 
There fore it seems that inequality is certainly a factor that make poeple more affected to droughts. 
## Drought and heatwaves

{% include Affected_interactive.html %}

The reason that we have chosen to invesitgate droughts is that the poeple that are are affected from them are increasing by decade. as shown in the above barplot.
Moerover. Droughts and riverine floods are the natural disasters that affect more the population and the last decade less poeple were affected from riverine floods.
Furtheremore, riverine floods have a geograohic dependency that droughts and do not have that much of a geographic dependecy.Furtheremore, it is visible from the following map that the more time passes the more countries are affected from droughts but also more population

{% include Map_before.html %}

### Drought 

The world health organization defines Drought as "a prolonged dry period in the natural climate cycle that 
can occur anywhere in the world. It is a slow-onset disaster characterized by the lack of precipitation, 
resulting in a water shortage. Drought can have a serious impact on health, agriculture, economies, energy, 
and the environment." 

Droughts are the biggest threat facing livestock and crops in almost every region of the world, affecting 
an estimated 55 million people annually. People's livelihoods are in danger, disease and death risks are 
raised, and mass migration is sparked by drought. 40% of the world's population suffers from water scarcity. 
By 2030, 700 million people could be at risk of being displaced due to drought.

Rising temperatures caused by climate change are already making dry regions drier, and wet regions wetter. 
This means that in dry areas, increasing temperatures cause water to evaporate more quickly, increasing the 
likelihood of drought or lengthening existing droughts. In the last ten years, floods, droughts, tropical 
cyclones, heat waves, and severe storms have been responsible for between 80 and 90% of all documented 
disasters caused by natural hazards.

### Heatwaves

Heatwaves often have variant definitions in different countries. The UK met office defines a heatwave as 
"an extended period of hot weather relative to the expected conditions of the area at that time of year, 
which may be accompanied by high humidity" (), while the US national weather service defines heatwaves 
as "a period of abnormally hot weather generally lasting more than two days. Heat waves can occur with or 
without high humidity" (). Most weather and meteorological institutions agree that heatwaves are prolonged 
periods of unusually high temperatures, often accompanied by excessive heat and humidity. These events pose 
significant risks to human health, particularly for vulnerable populations such as older people, young 
children, and those with pre-existing medical conditions. Heat-related illnesses, heat strokes, and even 
deaths can occur during heatwaves. They may also put stress on energy systems, increasing the need for 
cooling and raising the possibility of power outages.

Droughts and heatwaves are natural phenomena that have significant impacts on both the environment and 
human populations. Understanding the causes, patterns, and effects of droughts and heatwaves is essential 
for developing effective strategies to mitigate their impacts and enhance resilience. Therefor a look at the 
relationship between economic and social indicators and effect of droughts and heatwaves of countries. 
To see if there are some correlation and clustering between these factors. 

## Dependencies with other financial factors

One of the sectors that are affected the most from the drought is the agricultural sector. In the following scaterplot. It is 
visible that the there is a positive correlation between the poeple that are affected. 

{% include  GDP_agriculture.html %}

More specifically it seems that the Cerial Yields of a coutry is decreased when more poeple are affected. 

{% include  Cerial_Yields.html %}



