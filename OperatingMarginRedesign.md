# Critique by Design

## Aggregate Operating Margins - Fiscal Year 2014
From Dance/NYC Report [*State of NYC Dance & Workforce Demographics 2016*](https://culturaldata.org/media/1452/state-of-nyc-dance-and-workforce-demographics-online-version.pdf)

![](AboutMePics/OMscreenshot.png)

### *notes*
For the chart above from the [Dance/NYC](https://culturaldata.org/media/1452/state-of-nyc-dance-and-workforce-demographics-online-version.pdf) report, *State of NYC Dance and Workforce Demographics 2016*, I was initially thrown off by all the identical bar lengths even though the "Unrestricted Revenue" and "Total Expenses" values were all different. This seemed odd for a bar graph where the whole point is to highlight comparative differences. Then I realized it was the operating margin (the bar within the bar) that was the focus of the chart. The bar sizes for the percentages across the five categories are proportional in relation to each other, but not at all proportional to their respective budget bars. I just couldn't grasp what was most important with all the numbers on the chart. Why include the average revenue and expenses if you’re not going to then correlate the operating margin to those values? I thought having the relationship of operating margin to budget size was an important piece of the story, but I really struggled to try and accurately reflect scale and include all the information on the original visualization. Especially because operating margin percentages kept getting bigger as the budgets got exponentially smaller. You can see in the first few sketches my attempts and trying to include relative scale. I thought perhaps some variation of a stack bar chart or treemap might work.

![](AboutMePics/Sketch_3:4.JPG)

My gut response was "it's not gonna work."

Feedback from others included:
* "It **minimizes** what's important."
* "Where will you **fit** the values?"
* "It doesn't emphasize that small dance organizations are **outperforming** big ones."

At that point, I gave up on trying to include budget as a volume in the visualization. So I tried a few more sketches to see if a some sort of scatter or dot plot might be more effective, still including revenue and expenses. But the scatter plot just drew even more attention to the correlation of those values and did little to highlight the operating margins. I really liked the look of the dumbbell plot, but ran into trouble with the scale of values on the double y-axis. Plus, it still didn't highlight the achievement of the smaller organizations. 

That's when I decided to just focus on the operating margin values and flip to a single vertical dot plot. That allowed the smaller organizations to literally be on top and the visualization wasn't drowning in so many unnecessary numbers.



## REDESIGNED - Aggregate Operating Margins
Made using [Flourish](https://flourish.studio/)

<div class="flourish-embed flourish-scatter" data-src="visualisation/4384351"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
