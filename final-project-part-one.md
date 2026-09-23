| [home page](https://pddpdd20020105.github.io/tswd-portfolio/) | [data viz examples](https://pddpdd20020105.github.io/tswd-portfolio/dataviz-examples) | [critique by design](https://pddpdd20020105.github.io/tswd-portfolio/critique-by-design) | [MakeoverMonday](https://pddpdd20020105.github.io/tswd-portfolio/makeover-monday) | [final project I](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-one) | [final project II](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-two) | [final project III](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-three) |

# Final Project Part I: When Do People Visit America's National Parks?

## Outline

### Project summary

I enjoy traveling, and one question I often have when planning a trip is when to visit. Summer seems like the obvious season for a national park trip, but does every park actually receive the most visits in summer? I want to use National Park Service (NPS) data to explore how visits change throughout the year and how those patterns differ between parks.

My intended audience is people planning a national park trip. The project will begin with the overall national pattern, then compare parks with contrasting peak months. Finally, readers will be able to explore the data for parks that interest them. My goal is to help readers use visitation patterns as one clue when choosing travel dates. Fewer recorded visits do not necessarily mean better weather, open roads, or fewer people at a particular attraction.

### Project structure and story

**Opening — The travel-planning question.** The page will begin by asking: *Is summer the busiest season at every national park?* This gives readers a practical reason to care about monthly visitation.

**Context — The national pattern.** A chart of monthly NPS recreation visits will show how visits vary across the United States during 2024. This establishes the pattern that readers might expect to see at every park.

**Surprise — Four parks, different seasons.** I will then compare Acadia, Great Smoky Mountains, Joshua Tree, and Yellowstone. My initial analysis of the 2024 data shows that their highest-visit months were August, October, March, and July, respectively. A chart showing each month's share of a park's annual visits will make these different seasonal patterns comparable.

**Exploration — What about a park I want to visit?** The final interactive section will allow readers to select a park and examine its monthly visitation pattern. This turns the story into a starting point for their own travel planning.

**Takeaway.** There is no single peak season that describes every national park. Readers should use historical visitation alongside current information about weather, access, and park conditions.

**One-sentence message:** National park visitation is seasonal, but the season depends on the park.

## Initial sketches

The following sketches show the proposed order and purpose of the main sections. These are plans for the final story, so their layout and visual details may change.

| Story section | Planned page element | What the reader should learn |
|---|---|---|
| Opening | Large question: **“Is summer the busiest season at every national park?”** followed by a short travel-planning introduction | Why the question matters |
| National context | Monthly line chart: **month → total NPS recreation visits in 2024** | The overall seasonal pattern |
| Four-park comparison | Four colored lines: **month → share of each park's annual visits** | Peak months differ across parks |
| Reader exploration | Interactive park selector with a monthly visitation chart | The pattern for a park the reader chooses |
| Closing | Short takeaway and a reminder to check current park conditions | How to interpret the data for a trip |

### Working prototype: four-park comparison

This is my first Tableau prototype for the comparison section. The vertical axis shows the percentage of each park's 2024 recreation visits that occurred in a given month. Using percentages makes it possible to compare the *shape* of each park's seasonal pattern without the largest park dominating the chart.



[Open the interactive prototype on Tableau Public](https://public.tableau.com/views/NationalParkVisitsbyMonth2024/Shareofeachparksannualvisits)

## The data

My primary source is the NPS Visitor Use Statistics Data Package. The `Main_Data` CSV has five fields: `UnitCode`, `Year`, `Month`, `Statistic`, and `Value`. For the initial visualizations, I filter `Statistic` to `TRV` (recreation visits) and `Year` to 2024. I then sum visits by month for the national overview. For each park comparison, I divide each month's visits by that park's total visits in 2024.

The copy of `Main_Data` that I downloaded contains data from 1979 through 2024, despite the catalog page being titled “2025.” I am therefore labeling my current analysis as **2024**. I also downloaded `Main_State_Data`, which includes state codes and covers 2016–2024 in my copy. I may use it if a state-level comparison helps the final story, but the current prototype uses `Main_Data`.

NPS defines a recreation visit as a visit, not a count of distinct people. One person can contribute visits on multiple days or at multiple parks. Monthly totals also cannot tell us how crowded a particular trail was on a particular day. I will explain these limitations wherever I discuss what the charts might mean for travel planning.

| Name | URL | Description |
|---|---|---|
| NPS Visitor Use Statistics Data Package | https://catalog.data.gov/dataset/nps-visitor-use-statistics-data-package-2025 | Public source of the monthly visitor-use CSV files |
| NPS Visitor Use Statistics Definitions | https://www.nps.gov/subjects/socialscience/nps-visitor-use-statistics-definitions.htm | Definitions used to interpret recreation visits |
| Initial Tableau prototype | https://public.tableau.com/views/NationalParkVisitsbyMonth2024/Shareofeachparksannualvisits | My first comparison of four parks |

## Method and medium

I plan to create a standalone, interactive story page linked from my GitHub Pages portfolio. I will prepare monthly summaries from the NPS CSV data and use Tableau Public to create the charts. The page will combine short narrative sections with visualizations so readers can follow the national-to-local story before exploring a park themselves. Before making travel decisions, readers should check each park's current conditions on the NPS website.

## References

- National Park Service. *NPS Visitor Use Statistics Data Package, 2025*. https://catalog.data.gov/dataset/nps-visitor-use-statistics-data-package-2025
- National Park Service. *NPS Visitor Use Statistics Definitions*. https://www.nps.gov/subjects/socialscience/nps-visitor-use-statistics-definitions.htm

## AI acknowledgements

I used ChatGPT to brainstorm the topic and story structure, interpret the assignment requirements and NPS data fields, troubleshoot the Tableau chart, and help draft this Part I outline. I checked the chart's patterns against the data and made the final choices about the project.
