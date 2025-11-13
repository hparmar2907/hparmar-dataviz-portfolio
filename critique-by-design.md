| [home page](https://hparmar2907.github.io/hparmar-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [Visualizing Government Debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Greenhouse Gases, Clearer: Redesigning NOAA’s Figure 4 for Comparative Insight
This project began as a critique of Figure 4 from NOAA’s Annual Greenhouse Gas Index (AGGI) report — a visualization showing the long-term increase of greenhouse gases since 1750. While the original figure is scientifically rigorous and visually clean, it’s primarily designed for technical audiences and makes it difficult to compare individual gases or explore specific time periods.

Using Stephen Few’s Data Visualization Effectiveness Profile, I analyzed the figure across seven criteria, identifying strengths in accuracy and completeness but weaknesses in intuitiveness and engagement. From there, I set out to redesign the visualization to make it more interactive, comparative, and accessible. My redesign allows users to click any year as a baseline and view how concentrations of each greenhouse gas have changed relative to that point, while also displaying the percentage change over time.

This portfolio entry documents my full process — from critique and sketches to feedback and redesign — and reflects on how small design choices can make complex scientific data more understandable and engaging for broader audiences.

## Step one: the visualization

**[Original Source](https://gml.noaa.gov/aggi/aggi.html)**  
I selected this data visualization because it offers a comprehensive, long-term view of greenhouse gas trends, tracing atmospheric CO₂ and total greenhouse gas forcing from 1750 to the present. The figure effectively communicates the magnitude of change over centuries and serves as an authoritative source grounded in scientific data. However, its design—while precise—feels heavily geared toward expert audiences. The technical terminology, dual y-axes, and lack of contextual cues (like key policy events or clearly marked baselines) make it difficult for general readers to interpret.

I found this visualization compelling because it sits at the intersection of scientific rigor and public communication. Climate data is inherently complex, and this figure captures that complexity beautifully but without much accessibility. That tension made it an ideal candidate for critique and redesign: I wanted to explore how thoughtful visual design and interactivity could make such information clearer, more comparative, and more engaging without sacrificing accuracy.


## Step two: the critique
Using Stephen Few’s Data Visualization Effectiveness Profile, I evaluated NOAA’s Figure 4 across seven criteria: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement. The figure is highly accurate and comprehensive, clearly depicting the long-term rise in greenhouse gases and the relationship between CO₂, CO₂-equivalent concentrations, and the AGGI index. It succeeds in its truthfulness and usefulness for technical audiences such as scientists and policymakers, offering reliable, well-cited data that supports evidence-based discussions.

However, the visualization also presents several accessibility and interpretability challenges. The use of dual y-axes requires additional cognitive effort and can confuse viewers unfamiliar with the difference between concentration and index values. Terms like AGGI and CO₂-equivalent abundance are not defined visually, making the figure less intuitive for non-experts. While the aesthetics are clean and professional, the chart lacks narrative or contextual elements—such as historical milestones, annotations, or interactive cues—that could make the data more engaging and easier to connect to real-world events.

Through this critique, I realized how small design choices—like labeling the 1990 baseline or providing a quick explanation of key terms—could make the visualization far more approachable without compromising accuracy. This analysis directly informed my redesign goals: to create a version that retains the scientific rigor of the original while improving comparability, interactivity, and overall user understanding.

## Step three: Sketch a solution
After completing my critique, I began thinking about how I could preserve the scientific precision of NOAA’s original visualization while making it easier for a broader audience to interpret. The critique process helped me identify two main issues: the lack of direct comparability between individual greenhouse gases and the static, expert-oriented design that limited engagement. I realized that the data itself was rich — the challenge was how to present it in a way that encouraged exploration. That insight shaped my redesign goals: to create something more interactive, comparative, and intuitive. I wanted users not only to see that greenhouse gases have risen but to actively explore how and by how much each one has changed over time. This led me to a small-multiples layout, where each gas would have its own panel, paired with an interactive feature allowing users to click any year to set a baseline and instantly view percentage changes relative to that point. What began as a critique of a static figure turned into a design exploration focused on turning climate data into a more accessible and engaging story.

<div class='tableauPlaceholder' id='viz1763046460057' style='position: relative'><noscript><a href='#'><img alt='Greenhouse gases have continued to increase in the atmosphere from 1979 to 2021But how do they compare to 2014?CLICK A YEAR TO COMPARE ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GreenhouseGases_17628966707180&#47;Sheet23&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GreenhouseGases_17628966707180&#47;Sheet23' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GreenhouseGases_17628966707180&#47;Sheet23&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1763046460057');                    var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

## Step four: Test the solution

Before finalizing my redesigned visualization, I wanted to understand how different users would interpret and interact with it. My goal was to see whether the new layout and features—like showing percentage change and allowing users to click a year to set a baseline—made the data easier to understand compared to the original NOAA figure.

To do this, I prepared a short interview script and conducted informal feedback sessions with three participants.Below is the set of questions I used to guide each discussion. I kept them open-ended to encourage honest and detailed feedback rather than yes/no answers.

Questions to ask: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

During the sessions, I took notes on participants’ initial reactions, the parts of the visualization that caught their attention, and the specific areas they found confusing or engaging. This feedback helped me identify which design choices worked well—such as the comparative panels and the inclusion of a total greenhouse gas line—and which elements needed refinement, like the interactivity instructions and color interpretation.

Some participants appreciated the color palette, saying it was clear and visually consistent, while others mentioned it was not immediately intuitive what the colors represented. Several users really liked that each gas was shown separately, along with an overall “total” panel, since it helped them make clearer comparisons. One user suggested improving the interactivity cue by changing the text from “Click a year to compare” to “Click a year on the line to compare”, which would make the action more specific and easier to discover. Another pointed out that certain gases followed very similar trends, and removing or combining them might simplify the visualization and reduce visual clutter.

Below are the detailed results from these interviews, followed by a synthesis of the main feedback themes and how I plan to incorporate those changes into the final redesign.

Results: 

After conducting short interviews with three participants — a **policy student**, an **engineer**, and a **non-technical graduate student** — I gathered feedback to evaluate how effectively the redesigned visualization communicated information and whether it was intuitive to use.

| **Question** | **Interview 1 (Policy Student)** | **Interview 2 (Engineer)** | **Interview 3 (Non-Technical Viewer)** |
|---------------|----------------------------------|-----------------------------|----------------------------------------|
| **What do you think this is?** | Understood that the visualization showed trends in different greenhouse gases over time. Found the separation of gases into individual panels helpful for comparison. | Identified that the chart compared gases individually and also included an overall total, which made it easy to understand the broader pattern. | Recognized that it displayed changes in multiple gases but was initially unsure about the interactivity until noticing the clickable line feature. |
| **What is this telling you?** | Observed that certain gases, such as CFCs, declined while others, like HFCs and CO₂, increased. | Noted that percentage-change values made the differences between gases clear. | Saw that CO₂ showed the most consistent and steep increase compared to others. |
| **Anything surprising or confusing?** | Mentioned that the color palette was attractive but not immediately clear in meaning. | Found the colors well-balanced and easy to read. | Suggested that some gases behaved similarly and might be combined or removed to simplify the layout. |
| **Who is the intended audience?** | Believed it would be useful for policymakers or students studying environmental trends. | Thought it was well-suited for technical or analytical users. | Felt that it could appeal to general audiences if small clarifications were added. |
| **Anything you would change?** | Recommended labeling key policy years, such as 1990 or 2015, to add context. | Suggested refining the instruction to say “click a year on the line to compare” for clarity. | Proposed adding a brief legend explaining the color gradient and simplifying redundant gases. |

Synthesis: 

The feedback revealed common themes around clarity, color interpretation, and interactivity. Participants liked the comparative layout, noting that showing both individual gases and the total trend made the visualization more comprehensive. Some suggested grouping gases with similar trends to simplify the view, while others preferred seeing each gas individually—so I plan to keep all gases visible.
The interactive elements were particularly well received. Several participants liked that hovering over a line displayed both the percentage change and the AGGI value, which helped them connect the trends to measurable impacts. A few viewers mentioned that the color palette could be refined for clearer meaning, and that the interactive instruction heading (“Click a year to compare”) could be more explicit. There were also suggestions to add contextual elements such as policy-year markers and a simple legend.

Based on this feedback, I plan to:

Refine the color palette for better clarity and differentiation.

Reword the interactive instruction to “Click a year on the line to compare.”

Retain all individual gases while emphasizing clearer visual separation.

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

