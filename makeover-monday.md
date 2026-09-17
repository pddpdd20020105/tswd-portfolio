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

However, the biggest issue is readability. The circular layout makes it difficult to quickly compare the trade balances of different countries because the bars extend in different directions around the circle rather than sharing a common baseline. For example, comparing Canada’s $34.9 billion surplus with Singapore’s $27.2 billion surplus requires the reader to visually trace bars positioned at different angles. There are also many visual elements competing for attention, which makes the chart feel somewhat crowded. While the visualization is effective at attracting attention and communicating the general idea, it is less effective for making detailed comparisons.

Based on this critique, I decided that my redesign should focus on making comparisons between countries easier. I plan to use a simpler layout, clearer labels, and fewer unnecessary visual elements.

### Reflection on the Critique Method

Stephen Few's Data Visualization Effectiveness Profile helped me evaluate the visualization from different perspectives instead of simply deciding whether I liked it. For example, I found the original visualization strong in aesthetics and engagement because the circular layout, colors, and country flags attract attention. However, when considering perceptibility and intuitiveness, I found that the same design makes it harder to compare values across countries.

Compared with the Good Charts method, I found this profile useful because it breaks a visualization into more specific qualities. However, some of the ratings still felt subjective. A visually engaging design may work well for a general audience even if it is less effective for precise comparisons. This made me realize that the effectiveness of a visualization also depends on its audience and purpose.

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

The final visualization shows that the U.S. had a services trade surplus with most of its free trade partners in the dataset. Canada had the largest services trade surplus at $34.9 billion, followed by Singapore at $27.2 billion and Australia at $16.0 billion. Only a few partners showed negative services trade balances, with the CAFTA-DR countries having the largest deficit at $6.3 billion.


### Final Visualization

<div class="tableauPlaceholder" style="position: relative;">
  <a href="https://public.tableau.com/views/U_S_ServicesTradeBalanceswithFreeTradePartners/Sheet1">
    <img
      alt="U.S. Services Trade Balances with Free Trade Partners"
      src="https://public.tableau.com/static/images/U_/U_S_ServicesTradeBalanceswithFreeTradePartners/Sheet1/1_rss.png"
      style="border: none; width: 100%;"
    />
  </a>
</div>

[View the interactive visualization on Tableau Public](https://public.tableau.com/views/U_S_ServicesTradeBalanceswithFreeTradePartners/Sheet1)

## AI Acknowledgement

I used Copilot to help brainstorm ideas for improving the visualization, organize parts of my written explanation, and troubleshoot Tableau and GitHub formatting. I reviewed and revised the suggestions before including them in my work. The final visualization was created by me in Tableau using the original dataset.
