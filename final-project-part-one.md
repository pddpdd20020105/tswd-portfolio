| [home page](https://pddpdd20020105.github.io/tswd-portfolio/) | [data viz examples](https://pddpdd20020105.github.io/tswd-portfolio/dataviz-examples) | [critique by design](https://pddpdd20020105.github.io/tswd-portfolio/critique-by-design) | [MakeoverMonday](https://pddpdd20020105.github.io/tswd-portfolio/makeover-monday) | [final project I](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-one) | [final project II](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-two) | [final project III](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-three) |

# Final Project Part I: More Visitors, More Money?

## Outline

### Project summary

National parks are often compared by how many people visit them. A park with millions of visitors may appear to have a much larger economic presence than a park with far fewer visitors. But does a higher number of recreation visits necessarily tell us the whole story about how much visitors spend in communities near national parks?

For this project, I want to combine National Park Service (NPS) visitation data with NPS visitor spending data for 2024. I will first examine the relationship between recreation visits and total visitor spending. I will then compare spending per recreation visit across national parks to explore whether parks with more visits also have higher spending on a per-visit basis.

My intended audience is people who are interested in national parks, tourism, and the economic relationship between parks and nearby communities. Rather than treating visitation as the only measure of a park's economic significance, I want readers to consider visitor spending as another way to understand differences among national parks.

My goal is not to argue that parks with higher spending per visit are "better" or more valuable. Recreation visits and visitor spending measure different things. Instead, I want to show why visitation alone does not tell the full economic story.

### Project structure and story

**Opening — More visitors, more money?** The story will begin with a simple question: *Do national parks with more visitors also generate more visitor spending?* It is reasonable to expect that parks receiving more recreation visits will generally be associated with more total visitor spending.

**Expectation — Visits and total visitor spending.** My first visualization will compare each national park's 2024 recreation visits with its estimated visitor spending. This will establish the overall relationship between popularity and visitor spending.

**Complication — Not every visit has the same spending pattern.** Total visitor spending is only one part of the story. I will calculate spending per recreation visit by dividing estimated visitor spending by recreation visits for each park.

**Surprise — Large differences between parks.** My initial exploration suggests that spending per visit varies substantially across national parks. Some parks with relatively few recreation visits have much higher spending per visit than some of the most heavily visited parks.

**Exploration — Why might these differences exist?** I will explore selected parks and use information available in the NPS Visitor Spending Effects data, such as visitor segments and trip characteristics, to investigate possible explanations for these differences.

**Takeaway.** More recreation visits are generally associated with more total visitor spending, but visitation alone does not tell the full economic story. Looking at both visitation and spending patterns provides a more complete picture of how national park tourism is connected to nearby communities.

**One-sentence message:** Visitation measures how heavily a national park is visited, but it does not by itself describe how much visitors spend in nearby communities.

## Initial sketches

The following sketches show my initial ideas for how the data story could develop. These are early Tableau prototypes rather than final visualizations. I plan to refine the visual design, annotations, park comparisons, and story structure as the project develops.

| Story section | Planned page element | What the reader should learn |
|---|---|---|
| Opening | Large question: **"More Visitors, More Money?"** | Introduce the assumption that more visitors should mean more visitor spending |
| Expectation | Scatter plot: **recreation visits → total visitor spending** | More heavily visited parks generally have higher total visitor spending |
| Complication | Comparison of **spending per recreation visit** across national parks | The amount of spending associated with each visit varies substantially between parks |
| Selected examples | Closer comparison of parks with contrasting visitation and spending patterns | Visitor counts alone do not explain all differences in visitor spending |
| Explanation | Explore trip characteristics and visitor segments for selected parks | Different types of trips may help explain differences in spending patterns |
| Closing | Short takeaway | Visitation is useful, but it does not tell the full economic story |

### Proposed page flow

The final story will be organized as a scrolling narrative so that each visualization builds on the previous section.

**Opening** → **Visits and total spending** → **Spending per visit** → **Contrasting parks** → **Possible explanations** → **Takeaway**

**Opening:** *More visitors, more money?*

**Visits and total spending:** A scatter plot establishes the overall relationship between recreation visits and estimated visitor spending.

**Spending per visit:** The story then changes perspective by comparing visitor spending relative to the number of recreation visits.

**Contrasting parks:** Selected national parks will illustrate how parks with very different visitation levels can also have very different spending patterns.

**Possible explanations:** Visitor segments and trip characteristics will provide context for why spending patterns may differ.

**Takeaway:** Recreation visits tell us how heavily a park is visited, but visitor spending provides another dimension of its relationship with nearby communities.

### Initial Tableau sketch 1: Recreation visits vs. visitor spending

This first prototype compares 2024 recreation visits with estimated visitor spending for U.S. national parks. At this stage, I am primarily interested in seeing the overall relationship between the two variables. I plan to refine the labeling, annotations, and visual design in later iterations.

<div class='tableauPlaceholder' id='viz1790962515068' style='position: relative'><noscript><a href='#'><img alt='Initial Sketch: Recreation Visits vs. Visitor Spending ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;PartIInitialSketchRecreationVisitsvs_VisitorSpending&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /><param name='embed_code_version' value='3' /><param name='site_root' value='' /><param name='name' value='PartIInitialSketchRecreationVisitsvs_VisitorSpending&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;PartIInitialSketchRecreationVisitsvs_VisitorSpending&#47;Sheet1&#47;1.png' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
var divElement = document.getElementById('viz1790962515068');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';
vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Initial Tableau sketch 2: Spending per visit by national park

The second prototype divides estimated visitor spending by recreation visits and compares the resulting spending-per-visit measure across national parks. The initial visualization shows substantial differences between parks and several clear outliers. Because this is an early prototype, the full set of parks is shown without additional annotations or visual emphasis. In later iterations, I plan to explore selected examples and alternative visual designs that make these differences easier to interpret.

<div class='tableauPlaceholder' id='viz1790962530372' style='position: relative'><noscript><a href='#'><img alt='Initial Sketch: Spending per Visit by National Park ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;PartIInitialSketchSpendingperVisitbyNationalPark&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /><param name='embed_code_version' value='3' /><param name='site_root' value='' /><param name='name' value='PartIInitialSketchSpendingperVisitbyNationalPark&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;PartIInitialSketchSpendingperVisitbyNationalPark&#47;Sheet2&#47;1.png' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
var divElement = document.getElementById('viz1790962530372');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';
vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## The data

This project uses two National Park Service datasets for 2024: the **NPS Visitor Use Statistics Data Package** and the **Visitor Spending Effects Data Package**.

The Visitor Use Statistics dataset provides monthly recreation visitation records for National Park Service units. For this project, I use `TRV` (recreation visits) and restrict the analysis to 2024 and units designated as national parks. I aggregate monthly recreation visits to calculate each park's annual recreation visits.

The Visitor Spending Effects dataset contains the visitor spending and trip-characteristics data used by NPS in its annual economic contribution analysis. The package includes monthly visitor segment shares, spending profiles, trip characteristics, and profile information. NPS uses information about visitation, visitor spending patterns in local gateway regions, and regional economic data to estimate the economic effects associated with visitor spending.

For my initial analysis, I combine the 2024 visitation and visitor spending information at the park level. I also calculate a simple derived measure:

**Spending per visit = Estimated visitor spending / Recreation visits**

This measure is intended as a way to compare spending relative to visitation. It should not be interpreted as the economic "value" of an individual visitor or as a measure of park quality. NPS recreation visits are visits rather than counts of unique people, and visitor spending is an estimate of trip-related spending associated with park visitation in nearby gateway regions.

| Name | URL | Description |
|---|---|---|
| NPS Visitor Use Statistics Data Package, 2024 | https://catalog.data.gov/dataset/nps-visitor-use-statistics-data-package-2024 | Public source of the NPS visitor-use data used for 2024 recreation visits |
| Visitor Spending Effects Data Package, 2024 | https://catalog.data.gov/dataset/visitor-spending-effects-data-package-2024 | Public source of the visitor spending profiles, visitor segments, and trip characteristics used in the project |
| NPS Visitor Spending Effects | https://www.nps.gov/subjects/socialscience/vse.htm | NPS information and interactive resources about visitor spending effects |

## Method and medium

I plan to create the final project as an interactive scrolling story using **Shorthand**, with data visualizations created in **Tableau Public**.

I will use Tableau to explore the relationship between recreation visits and visitor spending, compare spending per visit across parks, and develop closer comparisons of selected national parks. The initial Tableau charts shown above are exploratory sketches. I expect the final visualizations to use clearer annotations, selected examples, and more intentional visual design as the story develops.

Shorthand will provide the narrative structure connecting the visualizations. The story will begin with the intuitive relationship between visitation and total spending, introduce spending per visit as a different perspective, and then explore selected parks that help explain why visitor counts alone do not tell the complete story.

My GitHub Pages portfolio will document the development process and provide a link to the completed Shorthand story.

## References

- National Park Service. *NPS Visitor Use Statistics Data Package, 2024*. Data.gov.
- National Park Service. *Visitor Spending Effects Data Package, 2024*. Data.gov.
- National Park Service. *2024 National Park Visitor Spending Effects: Economic Contributions to Local Communities, States, and the Nation*.

## AI acknowledgements

The project topic and final decisions are my own. I used ChatGPT to help organize the revised story structure, identify relevant fields in the NPS datasets, combine the visitation and visitor spending data for exploratory analysis, and troubleshoot Tableau. I reviewed the results and made the final decisions about the project argument, visualizations, and narrative.
