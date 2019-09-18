# Assignments 3 & 4 - Critique by Design

For this assignment, I chose to critique a visualization from a government website: https://chapter55.digital.mass.gov/

Chapter 55 of the Acts of 2015, or just Chapter 55 for short, was a large scale endeavor by Masschusetts to combat the opioid epidemic by examining and synthesizing information from large quantities of data from 29 government agencies[1].

I selected this site for two reasons. First and foremost, the opioid crisis interests me. Secondly, I was interested in critiquing a government visualization because I believe the government should be held to high standards in the way the present information to the general public.

The site contains many visualizations, and most of them are pretty good in my opinion. They aren't all super flashy or aesthetically pleasing, but they present the data well and I can pick up their purpose almost instantly. For critique, however, I chose a visualization that was part of a, interactive dashboard, titled "Deadly Trend: Switching from Legal to Illegal Opioids" about halfway down the page, under the "Prescription" section. Here is an image of the bottom half of the dashboard, which contains the visualization:

![Chapter 55](https://jhumes.github.io/Humes-Portfolio/images/Assignment_3-4/ch55_Opioid_Viz.PNG)
Image source: "The Massachusettes Opioid Epidemic. A Data Visualization from the Findings of the Chapter 55 Report." https://chapter55.digital.mass.gov/. Accessed Sept. 18, 2019.

My main issue with the visualization is that most of the important information wasn't in the visualization. The important numbers and context information are all contained in text above the visualization, or in the header/legend just above it. If you cover up all the stick figure people with your hand, you still glean the exact same information from the image. Among other smaller issues, I didn't think using the figure people was the best way to represent proportions. I think the designers wanted it to "hit home" and feel more humanized by represented the deaths as a small proportion of people, but I think the cognitive load of looking at the people and maybe even having to count them is just too high. I also wasn't a fan of the red color choice due to its negative connotation that might apply between the two categories.

In general, the critique method we used really got me thinking. After a preliminary glance through the page, I wasn't really sure that any of them were so terrible that I wanted to redesign them. But as I went through more carefully and thought carefully about the things we had leanred like color and where the important information is actually contained, it actually became easy to find things I would change, and I thought this one was the worst on the page by a long shot. I also thought a lot about cognitive load when viewing them, paying a lot of attention to how easy it was for me to extract meaning. I think reducing cognitive load is most important when delivering information to a general audience of nonexperts - and the government does that a lot (I presume).

When drafting a redesign, two methods came to mind. I could use a simple treemap, which would act similar to a pie chart and show the same information from their visualization in a simpler way. The other was to use an alluvial diagram, which would capture way more information by showing all of the categories of information types on the dashboard, such as the presence of heroin, fentanyl, and other sorts of tests from the toxicology reports that made up the dataset. Here is what my draft looked like:

![Wireframe](https://jhumes.github.io/Humes-Portfolio/images/Assignment_3-4/Wireframe.jpg)

To simulate presenting information to an audience of non-experts, I presented the wireframe to two members of my immediate family. The consensus among them was that they had no idea what the alluvial diagram really was. But both understood relatively easily that the treemap was sort of like a pie chart, which was something much more familiar. In the end, I decided to go with the treemap. It's the most simple, and it only contains the same information that the section dashboard wanted to display. The original spirit of the dashboard was to emphasize the proportion of toxicology reports in a category, which makes the alluvial diagram less optimal since it excels at showing flow between categories. Here is the final result, which I made in Tableu:

![Tableu Treemap](https://jhumes.github.io/Humes-Portfolio/images/Assignment_3-4/ch55_treemap.png)

Going from wireframe to final draft, I decided to make the blocks in the treemap horizontal rather than stacking them on top of each other like the wireframe does. It was the default in Tableu, and it looks better because there's no connotation associated with one category being literally on top of the other. Overall, my goal was to remain true to the spirit of the original visualization, but just present the information in a cleaner way, with all of the good information on the visual with little cognitive load.

[Return to Portfolio](https://jhumes.github.io/Humes-Portfolio/)

##References
1. "The Massachusettes Opioid Epidemic. A Data Visualization from the Findings of the Chapter 55 Report." https://chapter55.digital.mass.gov/. Accessed Sept. 18, 2019.
