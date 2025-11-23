| [home page](https://hparmar2907.github.io/hparmar-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [Visualizing Government Debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# From Stability to Strain: How Rising Costs Are Outpacing Student Earnings

# Storyboards
When I began this project, my initial goal was straightforward: I wanted to compare how much housing costs had changed over time. But after classroom feedback and the critique-by-design exercise, it became clear that the story wasn’t just about housing or inflation—it was about something deeper and more relatable. Students today are facing a widening financial gap where the cost of simply existing (rent, food, tuition) is rising much faster than what they earn.

This realization shifted the entire scope of the project. Instead of looking at isolated datasets, I expanded the analysis to include housing CPI, food CPI, tuition costs, and student earnings. Bringing these datasets together allowed me to tell a fuller, more honest story of the student financial reality today—one where budgets are tighter, trade-offs are harsher, and affordability is becoming increasingly out of reach.

The structure of the storyboard follows this progression:

Start with cost-of-living pressures — showing how basic necessities like housing have risen year after year.

Layer in tuition costs — revealing how education affordability has changed in the same timeframe.

Contrast both with student earnings — highlighting the imbalance between rising expenses and stagnant wage growth.

This narrative shift allowed me to move beyond simply describing what costs look like, and instead begin exploring why students feel more financially strained today, even compared with just ten years ago. It also helped uncover a core insight: the issue isn’t just inflation—it’s that income is not keeping pace.

Ultimately, this project is not only about numbers. It’s about understanding the student experience in a landscape where everything feels more expensive except the one thing students rely on the most: their paycheck. A chart about CPI becomes a chart about affordability. A line showing tuition becomes a line showing the trade-off between education and financial stress. And when viewed together, the story becomes clearer: today’s students are being financially outpaced by their environment.

I will use this storyboard as the foundation for my Part III draft in Shorthand, where I will refine the narrative, integrate the Tableau visualizations, and strengthen the overall flow and clarity.

## The Introduction: Understanding the Rising Cost of Living for Students
The story begins with a simple but important question:
How much more expensive has it become to be a student today?

I start with my Housing CPI Over Time visualization, which shows how housing costs have risen sharply from 2015 to 2024. The line isn’t just increasing — it accelerates noticeably after 2021. This chart establishes the foundation: essential living costs have been climbing steadily, and students today are entering a financial environment that is fundamentally more expensive than it was a decade ago.
<div class='tableauPlaceholder' id='viz1763905760416' style='position: relative'><noscript><a href='#'><img alt='Housing Costs Have Risen Sharply Over the Past DecadeMeasured using the Housing Consumer Price Index (CPI), where 1982–84 = 100 (annual average).Source: U.S. Bureau of Labor Statistics (CPI Housing Index, 2015–2024). ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch1&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ProjectSketch1&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch1&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'> var divElement = document.getElementById('viz1763905760416');                    var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>


From here, I layer in food-related cost pressures. My Food-at-Home CPI Trends visualization highlights the consistent rise in grocery expenses, reinforcing that students are feeling cost increases in every basic necessity — rent, meals, utilities, and daily living. Together, these charts show that the financial strain is not isolated; it’s systemic.
<div class='tableauPlaceholder' id='viz1763907682054' style='position: relative'><noscript><a href='#'><img alt='Groceries Have Become Significantly More Expensive Over the Past DecadeMeasured using the Food-at-Home Consumer Price Index (CPI), where 1982-84 = 100 (annual averages)Source: U.S. Bureau of Labor Statistics ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch2&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ProjectSketch2&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch2&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /><param name='filter' value='showOnboarding=true' /></object></div><script type='text/javascript'> var divElement = document.getElementById('viz1763907682054');var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

## The Middle: Tuition Costs and the Financial Gap
After exploring how the cost of everyday essentials — housing and groceries — has risen sharply over the past decade, the story shifts to another major financial burden for young adults: the cost of higher education.

To understand how college affordability has changed, I use the Average Total Cost of Attendance for 4-Year Institutions dataset from NCES (Table 330.10). This metric includes tuition, mandatory fees, room, and board across all institution types:
public, private nonprofit, and private for-profit colleges.

In my visualization, the upward pattern is unmistakable. From 2010 to 2023, the total cost of attending a 4-year college has risen every single year, increasing from roughly $22,000 to over $31,000 annually. Even during periods of slower inflation, education costs continued climbing steadily, outpacing wage growth for many families.

What’s important to note — and what surprised me as I worked with this dataset — is that these figures may look lower than typical tuition numbers people hear about in the news. This is because NCES reports a national weighted average across all four-year institutions, including large numbers of lower-cost public in-state universities.
It does not represent the sticker price of individual private colleges, which is why the national average is significantly lower than many people expect.

Still, even this “smoothed-out” national average shows a clear trend:
the cost of earning a degree continues to rise, adding yet another financial layer to the already-increasing costs of housing and food.

This section transitions the story from basic living costs to a more structural financial challenge: the growing gap between the cost of education and the financial stability young adults need to achieve it.
<div class='tableauPlaceholder' id='viz1763914111514' style='position: relative'><noscript><a href='#'><img alt='The Total Cost of Attending a 4-Year College Has Risen Every Year Since 2010Includes tuition, fees, room and board (All institutions)Source: NCES Digest of Education Statistics, Table 330.10. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch3&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ProjectSketch3&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch3&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'> var divElement = document.getElementById('viz1763914111514');                    var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';  vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

But rising tuition is only one side of the story. The other side is a student’s ability to pay for that education. Most full-time undergraduates work part-time — typically around 20 hours per week across a 35-week academic year. Using median weekly earnings for young workers from BLS data, I estimated how much a student can realistically earn in a year.

When we compare these earnings to the rising cost of attendance, the gap becomes strikingly clear:
even a hardworking student with consistent part-time hours cannot keep pace with the increasing cost of college.

This financial gap is a core part of the modern student experience, and the visualization below makes that widening divide impossible to ignore.
<div class='tableauPlaceholder' id='viz1763921721639' style='position: relative'><noscript><a href='#'><img alt='The Real Financial Gap: Students Cannot Keep Up With Rising College CostsCosts are rising faster than what students can earn from typical part-time work (20 hours&#47;week × 35 weeks).Source: NCES Table 330.10 (inflation-adjusted cost)BLS CPS Weekly Earnin ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch4&#47;Sheet6&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ProjectSketch4&#47;Sheet6' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProjectSketch4&#47;Sheet6&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>  <script type='text/javascript'> var divElement = document.getElementById('viz1763921721639'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';  vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

## The End: What These Rising Costs Mean for Young Adults Today
After looking at housing, groceries, tuition, and the widening financial gap, the final takeaway becomes clear:

Young adults today are entering adulthood facing higher baseline living costs than any recent generation. 
Housing — the largest monthly expense — has steadily climbed year after year. Groceries, once a stable category, spiked sharply after 2020 and remain elevated. And higher education, long viewed as the pathway to upward mobility, has become substantially more expensive while part-time student earnings have barely kept up.

In isolation, each chart tells a story of gradual increase.
But together, they reveal something more powerful:
 - Every major cost required to build a stable adult life is rising at the same time.
 - These increases outpace what young people can earn while in school.
 - This squeezes students academically, financially, and emotionally.

For many, this means taking on more loans, delaying milestones like moving out, or working longer hours — often at the cost of sleep, mental health, and academic performance. The data brings into focus the everyday reality behind headlines about affordability and “cost-of-living crises.”

But the story isn’t just about struggle — it’s about awareness.

By understanding where and how costs are rising, we can start conversations about support, policy, and systems that genuinely reflect the financial realities students face today.

# User research 
To refine my storyboard and ensure that my narrative communicates clearly to a non-technical audience, I conducted user research with three individuals who closely represent my intended readers. The goal of this process was to understand how effectively my early wireframes and visual drafts conveyed the rising cost pressures on students, and to identify areas where the clarity, emotional impact, or flow could be improved.
## Target audience
The primary target audience for this story is:

- Current students
- Recent graduates
- Young adults preparing for or considering college

These individuals are often directly affected by rising living expenses, financial aid gaps, and the increasing cost of higher education. They may not be data experts, but they are highly invested in understanding how affordability impacts their lives, choices, and long-term stability.

### Approach for Identifying Participants

I selected three people from my network who reflect different experiences within this audience. Each participant brings a distinct perspective on college affordability and financial stress:

#### Participant A — Current Undergraduate Student

Struggles with balancing part-time work and academic commitments; highly sensitive to changes in food and housing costs.

#### Participant B — Recent Graduate

Currently repaying student loans; has firsthand experience budgeting rent, groceries, and transportation right after graduating.

#### Participant C — Prospective Graduate Student

Actively researching tuition and living expenses while deciding whether to continue their education; very interested in understanding long-term financial tradeoffs.

## Interview Script

| **Goal** | **Questions** |
|----------|---------------|
| **Assess story flow** | What was your initial impression of the flow (housing → food → tuition → financial gap)? Did the sequence make sense? |
| **Evaluate clarity of visuals** | Were the charts easy to understand? Which visualization was clearest to you, and why? |
| **Identify confusing elements** | Did any chart, label, or number confuse you? Was anything difficult to interpret? |
| **Explore engagement & surprises** | Which part of the story caught your attention? Did any data point surprise you? |
| **Gather suggestions** | What changes would make the visuals or narrative clearer? Is anything missing? |
| **Check narrative framing** | Does the story feel more about student experience or broader economic trends? Which framing feels more impactful? |


## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

| Questions               | Interview 1 (briefly describe) | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| Question you asked here | Insightful feedback            |             |             |
|                         |                                |             |             |
|                         |                                |             |             |


# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

Text here!

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Findings or observations from interviews | Describe what, if any changes you anticipate making to address the observation. |
|                                          |                                                                                 |
|                                          |                                                                                 |
|                                          |                                                                                 |
| ...add more rows as necessary            |                                                                                 |

> ...include any final thoughts you have here. 

Text here!

# Moodboards / personas
> If you did this optional part, include details here.  Otherwise remove this section

Text here!

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

