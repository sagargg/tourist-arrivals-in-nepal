---
datapackage:
  title:
  description: Tourism in Nepal
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  sources:
  - path: https://www.tourism.gov.np//downloads
    title: 
  resources:
  - name: number-of-international-tourist-arrivals-by-year-1993–2023
    title: Number of international tourist arrivals by year, 1993–2023
    format: CSV
    description: 
    path: tourism-data.csv
---


# Number of international tourist arrivals by year, 1993–2023
This data shows the annual number of international tourists arriving in Nepal from 1993 to 2023 and the year-over-year changes, highlighting growth trends, significant declines due to events like the 2015 earthquake and the 2020 COVID-19 pandemic, and strong recovery phases, particularly in 2022 and 2023.

# Key Points
- 1993-2000: A period of steady growth with occasional minor declines, reflecting a generally positive trend in tourism.
- 2001-2002: Sharp declines due to global and local issues.
- 2003-2014: A steady recovery and growth phase, with only minor fluctuations.
- 2015: A significant impact year due to the earthquake.
- 2016-2019: Rapid recovery and growth, leading to peak tourist numbers.
- 2020: Severe impact of the COVID-19 pandemic.
- 2021-2023: Recovery phase post-pandemic, with substantial increases in tourist numbers.

#  Chart 

<LineChart
  data={{ url: "tourism-data.csv" }}
  title="Number of international tourist per each year"
  xAxis="year"
  yAxis="number_of_tourists"
/>


<PlotlyLineChart
  data={{ url: "tourism-data.csv" }}
  title="Number of international tourist per each year"
  xAxis="year"
  yAxis="number_of_tourists"
/>