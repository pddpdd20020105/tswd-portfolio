| [home page](https://pddpdd20020105.github.io/tswd-portfolio/) | [data viz examples](https://pddpdd20020105.github.io/tswd-portfolio/dataviz-examples) | [critique by design](https://pddpdd20020105.github.io/tswd-portfolio/critique-by-design) | [MakeoverMonday](https://pddpdd20020105.github.io/tswd-portfolio/makeover-monday) | [final project I](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-one) | [final project II](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-two) | [final project III](https://pddpdd20020105.github.io/tswd-portfolio/final-project-part-three) |

# Final Project Part III: More Visitors, More Money?

# The final data story

My final data story examines the relationship between national park visitation and visitor spending. The project began with a simple question: do national parks with more recreation visits also tell the biggest economic story?

The final story first establishes the expected relationship between recreation visits and total visitor spending. It then changes perspective by comparing estimated spending per recreation visit across parks. This reveals substantial differences that are not visible from visitor counts alone. Finally, the story explores length of stay as one possible clue for understanding why park trips can have different spending patterns.

The central message remained consistent throughout the project: recreation visits are useful for understanding how heavily a park is visited, but visitation alone does not capture the full economic story. The final version makes the next step more explicit by encouraging readers to consider spending per visit and trip characteristics alongside total visitation when evaluating the economic contribution associated with national park tourism.

[View the final Shorthand data story](https://carnegiemellon.shorthandstories.com/more-visitors-more-money/index.html)

# Changes made since Part II

The overall argument and structure of the project remained consistent from Part I through the final version. In Part I, I proposed moving from the familiar relationship between visitation and total visitor spending to a comparison of spending per recreation visit, followed by a closer exploration of trip characteristics. I also created early Tableau sketches and selected Shorthand as the medium for connecting the visualizations through a scrolling narrative.

In Part II, I developed those early sketches into higher-fidelity Tableau visualizations and a working Shorthand prototype. I then conducted user research with three potential readers to test whether the central argument, narrative progression, and visualizations were understandable. The feedback suggested that the overall story was working, but it also identified several areas where the explanatory section could be more precise.

One change involved the length-of-stay section. In the Part II version, the term "LodgeOut" appeared without a clear explanation, and user feedback showed that this terminology could be confusing. In the final version, I replaced the technical term with the more accessible phrase "visitors staying overnight outside the park." I also added context explaining that I compared a small group of parks with different visitation and spending-per-visit patterns.

I also narrowed the section that asks what might explain differences in spending per visit. The Part II prototype mentioned length of stay, visitor origin, and spending patterns as possible characteristics to explore, but only length of stay was actually analyzed later in the story. Instead of adding additional visualizations simply to cover all of these possibilities, I revised the final version to focus on the evidence that is actually presented: length of stay. This made the transition into the final visualization more direct and kept the scope of the story focused.

Another important change was strengthening the ending. The Part II version primarily concluded that visitor counts do not tell the whole economic story. In the final version, I added a clearer call to action: when evaluating the economic contribution of national parks, readers should not rely on visitation counts alone, but should consider spending per visit and trip characteristics alongside total visitation.

Throughout these revisions, I also kept the language around length of stay cautious. The final story presents length of stay as one possible clue rather than claiming that longer stays cause higher spending per visit. The analysis shows associations and differences between park trips, but it does not establish a causal relationship.

## The audience

My intended audience is a general audience interested in national parks, tourism, and the economic relationship between parks and nearby communities. In particular, the story is designed for readers who may initially assume that the most heavily visited parks necessarily tell the largest economic story.

I did not assume that readers would have prior knowledge of National Park Service visitor spending data or economic analysis. This influenced the narrative structure of the project from the beginning. The story starts with visitor counts and total spending, which are relatively intuitive measures, before introducing spending per recreation visit as a different way of comparing parks.

The Part II user research helped me refine the story for this audience. Participants generally understood the central argument, but their feedback showed that technical terminology and unexplained transitions could make the later part of the story harder to follow. For the final version, I therefore simplified the language around the length-of-stay data, clarified the purpose of the selected park comparison, narrowed the explanatory section to the evidence actually shown, and made the final recommendation more explicit.

## Final design decisions

One of my main design decisions was to preserve the narrative progression that developed from my initial Part I wireframe:

**Opening question → visitation and total spending → spending per visit → length of stay → takeaway and action**

Each visualization serves a different purpose in this progression. The first establishes the expected positive relationship between recreation visits and total visitor spending. The second changes the unit of comparison to spending per recreation visit and reveals the main complication in the story: parks with very different visitation levels can also have very different spending patterns. The third then explores length of stay as one example of how the characteristics of park trips can differ.

I decided not to add additional visualizations for visitor origin or other spending patterns in the final version. Although these could provide interesting directions for future analysis, the Part II feedback showed that the more important issue was making the existing explanation clearer. Adding more information would also have expanded the scope of the story beyond what was necessary to support the central argument.

I kept Shorthand as the final medium because the scrolling format allows the argument to unfold in a controlled sequence. Rather than presenting the Tableau visualizations as separate charts, each section creates a question or expectation that the next visualization helps address. This structure supports the movement from an intuitive assumption to a more nuanced interpretation of the data.

The final call to action was another deliberate design decision. I wanted the story to end with more than a summary of the findings. The final section therefore asks readers to apply the central idea of the story: when interpreting the economic contribution associated with national park tourism, visitation should be considered alongside spending per visit and characteristics of the trip.

## References

This project uses 2024 National Park Service Visitor Use Statistics and Visitor Spending Effects data.

- National Park Service. *NPS Visitor Use Statistics Data Package, 2024*. Data.gov.
- National Park Service. *Visitor Spending Effects Data Package, 2024*. Data.gov.
- National Park Service. *2024 National Park Visitor Spending Effects: Economic Contributions to Local Communities, States, and the Nation.*

Detailed source information is also provided with the visualizations in the final Shorthand story. Additional information about the datasets, derived spending-per-visit measure, and interpretation limitations is documented in Parts I and II of the project.

## AI acknowledgements

The project idea, argument, and final decisions are my own. I used ChatGPT throughout the project to help refine the story structure, assist with data analysis, troubleshoot Tableau, organize user research findings, and revise wording for clarity. I used Google Gemini during the development of the Shorthand story and AI-assisted tools in Shorthand to help with aspects of the presentation and layout. I reviewed all AI-assisted work and made the final decisions about the analysis, visualizations, narrative, and revisions.

# Final thoughts

One of the most important things I learned through this project is that adding more data does not necessarily make a data story stronger. My initial plan already included the possibility of exploring multiple visitor segments and trip characteristics. By Part II, I had identified several possible explanations for differences in spending per visit. However, user research showed that the more important challenge was making the existing argument clear and ensuring that every part of the story was supported by the evidence actually presented.

For the final version, I therefore focused on refinement rather than expansion. I simplified terminology, clarified transitions, narrowed the explanatory section, and strengthened the conclusion. This process also showed me the importance of distinguishing between what the data demonstrates and what it only suggests. Length of stay can provide useful context for differences between park trips, but the current analysis cannot show that longer stays cause higher spending per visit.

If I continued developing the project, I would consider adding multiple years of data to examine whether the spending-per-visit patterns remain consistent over time. I would also be interested in exploring regional differences or additional trip characteristics. For this final version, however, I chose to keep the scope focused on the central argument: visitor counts are important, but they do not tell the whole economic story.
