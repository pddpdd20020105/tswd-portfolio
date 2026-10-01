| [home page](https://pddpdd20020105.github.io/tswd-portfolio/) | [data viz examples](https://pddpdd20020105.github.io/tswd-portfolio/dataviz-examples) | [critique by design](https://pddpdd20020105.github.io/tswd-portfolio/critique-by-design) | [MakeoverMonday](https://pddpdd20020105.github.io/tswd-portfolio/makeover-monday) | [final project I](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-one) | [final project II](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-two) | [final project III](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-three) |

# Final Project Part II: When Do People Visit America's National Parks?

In Part I, I developed the initial concept and story structure for a project about seasonal visitation patterns at U.S. national parks. For Part II, I developed that outline into a working Shorthand story, created higher-fidelity data visualizations, and began user research to evaluate whether the narrative and visualizations are clear to potential readers.

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

For user research, I am asking at least three people to review the Shorthand prototype and complete a short feedback survey. I am recruiting students and peers who can reasonably represent potential readers of a travel-oriented data story. I am not collecting names or other personally identifiable information.

Participants first view the Shorthand prototype and then complete a short Google Form. The survey focuses on whether the main message is clear, whether the narrative progression is easy to follow, whether the visualizations are understandable, and whether the planned individual-park interaction would be useful.

## Research Goals and Interview Script

The main goal of the research is to determine whether readers understand the intended narrative: national park visitation may peak in summer overall, but individual parks can have very different seasonal patterns. I also want to identify parts of the story or visualizations that need additional explanation before Part III.

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

**Background:** A first-year MISM-BIDA student at CMU, one academic year behind me.

The participant found the main message **very clear**, the transition from the national trend to individual parks **very easy to follow**, and the visualizations **very easy to understand**. They also thought the planned interactive park selector would be **very useful**.

Their interpretation of the main takeaway closely matched the intended narrative: although national park visitation generally peaks during the summer, individual parks can have very different seasonal patterns. They suggested adding the interactive park selector so readers can investigate parks they are personally interested in. They also suggested briefly providing context for why different parks may peak in different seasons, such as weather, road accessibility, or seasonal attractions.

A key observation from this participant was:

> "Looking at each park separately gives visitors a much better idea of when it is actually busiest."

## Participant 2

*Feedback pending.*

## Participant 3

*Feedback pending.*

## Research Synthesis

*This section will be completed after responses from all participants have been collected. I will compare the responses to identify recurring feedback, differences between participants, and issues that should be addressed in Part III.*

# Identified Changes for Part III

The current planned changes are preliminary because user research is still in progress. I will update this section after reviewing feedback from all participants.

| Research synthesis | Anticipated changes for Part III |
|--------------------|----------------------------------|
| Participant 1 found the overall message, narrative transition, and visualizations easy to understand. | Preserve the current overall narrative structure and progression from national trends to individual parks. |
| Participant 1 considered an individual-park selector very useful. | Develop the planned interactive park selector so readers can explore monthly visitation patterns for a park they are personally interested in. |
| Participant 1 suggested explaining why seasonal patterns may differ between parks. | Explore whether brief contextual information can be added using appropriate external sources. Avoid attributing causes to weather, road access, or seasonal attractions unless they are supported by evidence. |
| Additional feedback | *Pending Participants 2 and 3.* |

After all responses are collected, I will look for similarities and differences across participants rather than making changes based on a single response. The final Part III revisions will prioritize issues that appear consistently across the user research while also considering useful individual observations.

## References

- National Park Service Visitor Use Statistics. Recreation visits (TRV), 2024.
- [Current Shorthand prototype](https://carnegiemellon.shorthandstories.com/when-do-people-visit-americas-national-parks/index.html)

## AI Acknowledgements

I used ChatGPT to help refine the narrative structure and wording of the Shorthand story, organize the user research protocol, and structure the Part II documentation. I also used ChatGPT to troubleshoot the embedding of Tableau visualizations in Shorthand and to help identify where additional explanatory text or data notes could improve clarity. I reviewed and edited the final content myself and made the final decisions about the story structure, visualizations, research questions, and design.

I used Google Gemini to generate an initial draft of the Google Form used for user research. I reviewed and edited the questions before distributing the survey.

I previously used GitHub Copilot during the development process to help organize project materials and troubleshoot technical implementation where applicable.
