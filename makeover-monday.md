| [home page](https://pddpdd20020105.github.io/tswd-portfolio/) | [data viz examples](https://pddpdd20020105.github.io/tswd-portfolio/dataviz-examples) | [critique by design](https://pddpdd20020105.github.io/tswd-portfolio/critique-by-design) | [MakeoverMonday](https://pddpdd20020105.github.io/tswd-portfolio/makeover-monday) | [final project I](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-one) | [final project II](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-two) | [final project III](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-three) |

# MakeoverMonday: America's Services Trade Balances

## Step 1: Choose a Data Visualization

For this assignment, I selected the visualization **"America's Services Trade Balances with Its Free Trade Partners."** The visualization shows the U.S. services trade balance with different free trade partners, including Canada, Singapore, Australia, South Korea, and others.

I selected this visualization because the circular design is visually interesting, but it makes it difficult to quickly compare the values across countries. I wanted to explore whether a simpler design could make the differences between countries easier to understand.

### Original Visualization

<img width="1200" alt="America's Services Trade Balances visualization" src="https://github.com/user-attachments/assets/72415624-679a-4005-8c67-8d7a303b84ee" />

**Source:** [MakeoverMonday – America's Services Trade Balances](https://makeovermonday.vercel.app/dataset/america-s-services-trade-balances-with-its-free-trade-partners)

**Data:** The original dataset was provided as an Excel file and includes trade balance data for goods, services, and goods and services combined.

## Step 2: Critique the Visualization

I evaluated the original visualization using Stephen Few's Data Visualization Effectiveness Profile. Overall, I found the visualization visually engaging and informative. The colors, country flags, labels, and circular design make the visualization attractive and help draw attention to the topic.

However, the biggest issue is readability. The circular layout makes it difficult to quickly compare the trade balances of different countries. There are also many visual elements competing for attention, which makes the chart feel somewhat crowded. While the visualization is effective at attracting attention and communicating the general idea, it is less effective for making detailed comparisons.

Based on this critique, I decided that my redesign should focus on making comparisons between countries easier. I plan to use a simpler layout, clearer labels, and fewer unnecessary visual elements.

## Step 3: Sketch a Solution

Based on my critique, I created a horizontal bar chart as my initial redesign. I sorted the countries by their services trade balances and added value labels to make comparisons easier.

The goal of this draft was to simplify the original circular design and make the differences between countries easier to see.

### Initial Redesign

<img width="997" height="238" alt="Initial redesign" src="https://github.com/user-attachments/assets/9daf17dc-8acf-411c-87e1-a3584c7cc793" />

## Step 4: Test the Solution

I shared my initial redesign with three graduate students and asked them to review the visualization without much explanation. Overall, they found the horizontal bar chart easier to read and compare than the original circular design.

| Participant | What worked? | What didn't work? | What questions came up? | What new inspiration arose? |
| --- | --- | --- | --- | --- |
| Graduate student, MISM-BIDA program | The bar chart makes the values easy to compare. | The chart could provide more context about what the data means. | What is the main takeaway from the visualization? | Add a short explanation to provide more context. |
| Graduate student, MISM program | The horizontal layout and data labels are clear and easy to read. | The chart looks a little plain with only one color. | Could color highlight important countries or values? | Use color to highlight important information. |
| Graduate student, MSPPM program | The differences between countries are easy to see. | The chart does not provide much geographic context. | Would a map help provide geographic context? | Consider adding a small map to provide geographic context. |

### What I Learned

The feedback showed that the simpler bar chart improved readability, which was the main goal of my redesign. However, simplifying the original visualization also removed some of its visual interest and context.

For my final redesign, I plan to keep the horizontal bar chart, but add more context about what the values represent and use color more intentionally. I will also explore whether a map could add useful geographic context without making the visualization too complicated.

## Step 5: Final Redesign

Based on the feedback from my peers, I refined my horizontal bar chart while keeping the simple layout that made country comparisons easier.

For the final redesign, I used a red-to-green color scale to distinguish services trade deficits from surpluses and to show differences in magnitude. I also added a short subtitle to provide more context and formatted the value labels in billions of dollars to make the chart easier to read.

I considered adding a map for geographic context, but decided not to include it because it would add complexity without improving the main comparison between countries.

### Final Visualization
<div class='tableauPlaceholder' id='viz1789667969359' style='position: relative'><noscript><a href='#'><img alt='U.S. Services Trade Balances with Free Trade PartnersThe U.S. recorded a services trade surplus with most partners, led by Canada and Singapore.Source: U.S. Bureau of Economic Analysis, 2024 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;U_&#47;U_S_ServicesTradeBalanceswithFreeTradePartners&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='U_S_ServicesTradeBalanceswithFreeTradePartners&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;U_&#47;U_S_ServicesTradeBalanceswithFreeTradePartners&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1789667969359');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
