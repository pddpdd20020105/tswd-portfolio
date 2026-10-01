| [home page](https://pddpdd20020105.github.io/tswd-portfolio/) | [data viz examples](https://pddpdd20020105.github.io/tswd-portfolio/dataviz-examples) | [critique by design](https://pddpdd20020105.github.io/tswd-portfolio/critique-by-design) | [MakeoverMonday](https://pddpdd20020105.github.io/tswd-portfolio/makeover-monday) | [final project I](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-one) | [final project II](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-two) | [final project III](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-three) |

# Final Project Part II: When Do People Visit America's National Parks?

In Part I, I developed the initial concept and story structure for a project about seasonal visitation patterns at U.S. national parks. For Part II, I developed that outline into a working Shorthand story, created higher-fidelity data visualizations, and conducted user research to evaluate whether the narrative and visualizations are clear to potential readers.

[View the current Shorthand story](https://carnegiemellon.shorthandstories.com/when-do-people-visit-americas-national-parks/index.html)

# Wireframes / Storyboards

For Part II, I developed the storyboard directly in Shorthand rather than creating a separate static wireframe. The current prototype follows a scrolling narrative that moves from a familiar assumption about national park travel to a comparison of individual parks.

The story currently follows this progression:

1. **Opening question:** Is summer really the busiest season across the country?
2. **Setup:** Summer seems like the obvious answer because of warm weather, long days, and summer vacations.
3. **National context:** A monthly visitation chart shows that, nationally, recreation visits rise through spring and peak in July.
4. **Turning point:** The national pattern does not tell the whole story.
5. **Four-park comparison:** Acadia, Great Smoky Mountains, Joshua Tree, and Yellowstone demonstrate different seasonal visitation patterns.
6. **Meaning for travelers:** The comparison shows that peak season depends on the specific park.
7. **Transition to exploration:** The story asks readers to think about the park they personally want to visit.
8. **Planned interaction:** The final version will include an individual-park selector so readers can explore monthly visitation patterns for a park of interest.
9. **Takeaway:** There is no single best time to visit. Historical visitation patterns can be one input into trip planning, but they should be considered alongside current park conditions.

The Shorthand prototype allows me to test the pacing of the story, the transitions between sections, and how the visualizations work within the narrative rather than evaluating each visualization in isolation.

## Draft Data Visualizations

I currently have two high-fidelity Tableau visualizations embedded in the Shorthand prototype.

### National monthly visitation

The first visualization shows monthly recreation visits across U.S. national parks in 2024. It establishes the national pattern and shows a clear summer peak, with July having the highest visitation.

The chart includes a descriptive title, month and visitation axes, an annotation identifying the July peak, and a data source note.

**Source:** National Park Service Visitor Use Statistics, recreation visits (TRV), 2024.

### Four-park seasonal comparison

The second visualization compares Acadia, Great Smoky Mountains, Joshua Tree, and Yellowstone. Instead of comparing raw visitor totals, I use each month's share of a park's annual recreation visits. This makes it easier to compare the shapes of the seasonal patterns even though the parks have very different total visitation levels.

The comparison shows that Yellowstone and Acadia have strong summer peaks, Joshua Tree peaks in a cooler month, and Great Smoky Mountains has a broader seasonal pattern with its highest monthly share in October.

**Source:** National Park Service Visitor Use Statistics, recreation visits (TRV), 2024.

# User Research

## Target Audience and Recruitment Approach

My primary audience is people who are interested in visiting U.S. national parks and may use historical visitation patterns as one piece of information when deciding when to travel.

For user research, I asked three MISM-BIDA 16-month students to review the Shorthand prototype and complete a short feedback survey. They can reasonably represent potential readers of a travel-oriented data story. I did not collect names or other personally identifiable information.

Participants first viewed the Shorthand prototype and then completed a short Google Form. The survey focused on whether the main message was clear, whether the narrative progression was easy to follow, whether the visualizations were understandable, and whether the planned individual-park interaction would be useful.

## Research Goals and Interview Script

The main goal of the research was to determine whether readers understood the intended narrative: national park visitation may peak in summer overall, but individual parks can have very different seasonal patterns. I also wanted to identify parts of the story or visualizations that need additional explanation before Part III.

| Goal | Questions to Ask |
|------|------------------|
| Evaluate the clarity of the overall narrative | How clear is the main message of the story? |
| Evaluate the story structure | Is the transition from the national trend to individual parks easy to follow? |
| Evaluate visualization readability | How easy are the data visualizations to understand? |
| Evaluate the planned interaction | Do you think an interactive individual-park selector would be useful? |
| Check whether readers understand the intended conclusion | What do you think the main takeaway of the story is? |
| Identify opportunities for improvement | What is one suggestion you have for improving the story? |

# Interview Findings

## Participant 1

**Background:** MISM-BIDA 16-month student.

The participant found the main message **very clear**, the transition from the national trend to individual parks **very easy to follow**, and the visualizations **very easy to understand**. They also thought the planned interactive park selector would be **very useful**.

Their interpretation of the main takeaway closely matched the intended narrative: although national park visitation generally peaks during the summer, individual parks can have very different seasonal patterns. They suggested adding the interactive park selector so readers can investigate parks they are personally interested in. They also suggested briefly providing context for why different parks may peak in different seasons, such as weather, road accessibility, or seasonal attractions.

A key observation from this participant was:

> "Looking at each park separately gives visitors a much better idea of when it is actually busiest."

## Participant 2

**Background:** MISM-BIDA 16-month student.

The participant found the main message **very clear**, the transition from the national trend to individual parks **very easy to follow**, and the visualizations **very easy to understand**. They also considered the planned interactive park selector **very useful**.

Their interpretation of the story was consistent with the intended takeaway. They understood that there is no single peak season for all U.S. national parks and recognized that Yellowstone and Acadia peak in summer, while Joshua Tree and Great Smoky Mountains follow different seasonal patterns.

Their main suggestion was to complete the interactive park selector mentioned near the end of the story. They felt that allowing readers to explore a park they are personally interested in would make the story feel more complete.

A key observation from this participant was:

> "There is no single 'peak season' for all U.S. national parks."

## Participant 3

**Background:** MISM-BIDA 16-month student.

The third participant had a more mixed response. They found the main message **somewhat clear** and the transition from the national trend to individual parks **mostly easy to follow**, but rated the visualizations **neutral** in terms of ease of understanding. They considered the planned interactive park selector **somewhat useful**.

They still understood the central takeaway that visitation patterns are seasonal and that the busiest months vary depending on the park. Their main suggestion was to provide more guidance around the visualizations because some charts contain a lot of information at once.

They recommended adding short explanations, annotations, or highlighted data points so readers can identify the most important patterns more quickly.

A key observation from this participant was:

> "A brief annotation or highlighted data point could make the key pattern easier to understand quickly."

## Research Synthesis

Overall, all three participants understood the central message that national park visitation is seasonal but that individual parks can have different peak periods. Participants 1 and 2 found the narrative and visualizations very easy to follow, while Participant 3 understood the story but found the visualizations less immediately clear.

Two participants independently emphasized that the planned interactive park selector would improve the story and allow readers to explore parks they are personally interested in. This suggests that the interactive exploration should be a priority for the next version.

The main difference in the feedback concerned visualization clarity. Participants 1 and 2 found the charts very easy to understand, while Participant 3 wanted more explanation and visual guidance. Based on this feedback, I plan to preserve the overall narrative structure while improving annotations and explanatory text around the visualizations.

# Identified Changes for Part III

| Research synthesis | Anticipated changes for Part III |
|--------------------|----------------------------------|
| All three participants understood that different parks can have different seasonal visitation patterns. | Keep the current overall narrative structure from the national pattern to individual park comparisons. |
| Participants 1 and 2 considered the planned individual-park selector very useful. | Develop the interactive park selector so readers can explore monthly visitation patterns for a park they are interested in. |
| Participant 3 found the visualizations less immediately clear and requested more guidance. | Add or refine short annotations and explanatory text around the visualizations to highlight the most important patterns. |
| Participant 1 suggested explaining why seasonal patterns may differ between parks. | Consider adding brief contextual information about factors such as weather, access, or seasonal conditions, but only when supported by appropriate sources. |

The user research generally supports the current direction of the story, but it also identifies two priorities for Part III: completing the individual-park exploration and making the visualizations easier to interpret quickly.

## References

- National Park Service. *NPS Visitor Use Statistics Data Package, 2025*. https://catalog.data.gov/dataset/nps-visitor-use-statistics-data-package-2025
- National Park Service. *NPS Visitor Use Statistics Definitions*. https://www.nps.gov/subjects/socialscience/nps-visitor-use-statistics-definitions.htm

## AI Acknowledgements

I used ChatGPT, Google Gemini, and Copilot to assist with wording, user research materials, and technical troubleshooting. All AI-generated suggestions were reviewed and edited by me, and I made the final decisions on the content, analysis, visualizations, and design.
