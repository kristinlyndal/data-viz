# A Dive Into Data on Refugees in the United States

Refugee support is a topic that is incredibly important to me. I believe we have an obligation to welcome refugees to the United States in an organized manner.

According to UNHCR, there are currently 84 million forcibly displaced people in the world today, more than any other time in history. 35 million of those forcibly displaced are children below 18 years of age. 

In 2017, my husband and I were a mentor family to a refugee family from Rwanda through Pittsburgh's [Hello Neighbor](https://helloneighbor.io), and I proudly serve on their board of directors. 

## Data Visualization on Refugee Resettlement

<img width="850" alt="Screen Shot 2022-09-19 at 4 49 28 PM" src="https://user-images.githubusercontent.com/112270597/191115229-1ffbbec3-292d-4bae-9e1e-a607346d964a.png">

When I first saw this graph, I was excited to find this kind of data. I thought the graph was good, but not great; a few design tweaks could help it sing. 

It wasn't until after looking at it for a while that I saw what was happening in 2021 and 2022. Despite raising the annual ceiling in 2021 and 2022, the Biden Administration has barely increased the number of refugees actually being resettled in the US. In 2022, there are an alarming number of spots left unfilled. It's one thing for our government to say they will do something and have good intentions, but it's really the results that matter. We must hold our government accountable. This is when I decided to tell a relevant story with the data about what is happening now. 

## Critique the Data Visualization 

When rating the data based on Stephen Few's Data Visualization Effectiveness Profile, the strengths are clear. This graph is useful, pretty complete, and very truthful. It can use some improvement on perceptibility, intuitiveness, and aesthetics. Engagement is the biggest weakness. 

* **Usefulness:** Migration Policy Institute’s visualization is very useful. Understanding trends in the annual ceiling and number of admitted refugees is incredibly valuable information, especially during a refugee crisis as we are now in with Afghan and Ukranian refugees. The graph presents a digestible amount of data. 
* **Completeness:** The visualization is easy to understand, though the scale makes it challenging to visually connect the year of annual ceiling with the year of number of admitted refugees in some places. Measures of the norm and historical values are very clear and complete. However, while the user could figure out the number of refugees that could have been admitted given the ceiling but were not, the user would need to do some easy math to determine this number.
* **Truthfulness:** The visualization is accurate and valid. A spot check on the data from other sources validates that correct, accurate information is presented. The scales are consistent and nothing is skewed. 
* **Aesthetics:** The aesthetics, while not beautiful, are certainly not ugly. The grid lines weigh it down, as does unnecessary bold, serif font, repetition of “K” in the y-axis. The colors are distinct, but perhaps a different hue would be more visually pleasing. 
* **Intuitiveness:** The graph is intuitive and communicates clearly the historial numbers for annual ceiling and number of admitted refugees. Not everyone will know what “FY” means, so that should be written out and clarified, especially a fiscal year of Oct 1 to Sep 30, which is untraditional. 
If someone is unfamiliar with the exact definition of refugee, the webpage provides an explanation. What is not as intuitive and easy to comprehend is the number of refugee spots left unfilled each year. It is easy to look past 2022, where the crucial information is, and focus on the earlier years. Why else would the designer have decided to include 3/4s of 2022 if that is not crucial to this graph? Including 3/4s of a year convolutes and complicates the graph; but it does so for a very good reason.
* **Perceptibility:** Perceptibility is good but not great. There are a lot of simple tweaks that would make this chart much easier to read. There are more grid lines than necessary and too much bold. A sans-serif font would be easier to read. The repetition of “K” in the y-axis is not needed if "(in thousands)" is added to the label. The “Refugees Admitted” label could be turned to make it easier to read, in addition there isn’t enough space between the y-axis label and counts. Not everyone knows what FY means, so this likely convolutes the title. And it is challenging to visually match up the dots year-to-year when there is space between Annual ceiling and Number of admitted refugees. Most importantly, the user would need to do some basic math to determine the number of refugee spots left unfilled each year, which is really the most important information on this chart. Given that it is challenging to visually match up the dots year-to-year, this is all the more challenging. That said, there are also a lot of good qualities to the graph that make it clear. The visualization type is appropriate. There is a simple amount of information presented. The colors are contrasting, easy to distinguish, and not overwhelming. The year is appropriately on the x-axis running left to right. 
* **Engagement:** It could be easy to miss a major point of this graph: despite drastically raising the annual refugee resettlement ceiling, the Biden Administration is leaving the largest number of refugee spots unfilled since 1980. This point would inspire people to talk about the data and to want to know why this is happening. 



## Sketch Out a Solution 

![sketch1](https://user-images.githubusercontent.com/112270597/191123572-1be0dd92-66cd-4deb-b926-5e2c0fb3082e.jpeg)

**Engagement:** Based on my critique, I decided to first tackle engagement and focus on the gap between the ceiling and number admitted. I took this information and made it into a bar chart that sorted in ascending order. I simplified the amount of data presented to highlight the story I wanted to tell: this year's gap between ceiling and admitted is the highest since 1980, by nearly double. 

**Perceptibility and Intuitiveness:** Not everyone knows what FY means, so I wrote out fiscal year rather than abbreviating it. Rather than make the user toggle between the dots, I made the math easy and listed the total number of spots open (annual ceiling minus number of admitted refugees). 

**Aesthetics:** I removed grid lines, unnecessary bold, and serif font, which weighed the previous graph down. 

**Update:** I updated the data to include resettlement numbers through August 31, 2022. During my research I found an article on [CBSnews.com](https://www.cbsnews.com/news/us-2023-refugee-cap-125000/) about resettlement during 2022. I think my redesigned graph would work well in an article like this. 

## User Testing

I showed this first sketch to an early 30s art museum interpreter. I was shocked when she emotionally told me this looked like an "ultra right-wing meme on Facebook." I realized that I hadn't cited my source (palm to forehead). 

I told her to imagine that this was shown on a reputable news site and that all of the data is accurate. She told me it still felt skewed because of the dates; it felt like dates were being cherry picked because the dates jumped around. 

After this conversation, I made the following adjustments:
* Added a sub headline: Top Fiscal Years with Refugee Spots Left Unfilled 1980-2022 
* Added my source: Source: Migration Policy Institute

I then showed this slightly adjusted sketch to a mid 40s refugee advocate. He said he understood that this year had nearly double the spots left unfilled as any other year since 1980. He thought it was critical of Biden, but since he already knew about the problems with bringing refugees into the US and how behind we are, the data made sense. 

I thought about the fact that he probably knew more about refugees in the US than most readers, and I decided that I should add a little more context to up the "trustworthy" factor:
* Added second sub headline: Despite doubling the spots available for refugee admission to the United States in 2022, most spots go unfilled during Afghan and Ukrainian crises.


## Design in Tableau: Build a Solution

# With One Month Left, Biden Administration Leaves Over 100,000 Open Refugee Spots Unfilled
### Despite doubling the spots available for refugee admission to the United States in 2022, most spots go unfilled during Afghan and Ukrainian crises. 

<div class='tableauPlaceholder' id='viz1663716696710' style='position: relative'><noscript><a href='#'><img alt='Top Fiscal Years with Refugee Spots Left Unfilled from 1980-2022 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USRefugeeUnfilledSpots1980to2022&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='USRefugeeUnfilledSpots1980to2022&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USRefugeeUnfilledSpots1980to2022&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663716696710');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
*Fiscal Year 2022 data from October 1, 2021 to August 31, 2022.

Source: [Migration Policy Institute](https://www.migrationpolicy.org/programs/data-hub/charts/us-refugee-resettlement)

## In-Class User Test

One final test, this time with my classmates. They found the chart compelling. They thought it still read as critical of Biden but not untrustworthy. They suggested that I make the 2022 bar red to make it look like an alert.

They said they missed some of the other data in the original chart, and they would like a comparison between the ceiling and number of admitted, where my redesign only showed the gap. I agree that the original chart has value, but it's not the story I want to tell. I hopped into office hours to discuss and decided to keep that aspect as-is.

## Final Solution

# With One Month Left, Biden Administration Leaves Over 100,000 Open Refugee Spots Unfilled
### Despite doubling the spots available for refugee admission to the United States in 2022, most spots go unfilled during Afghan and Ukrainian crises.

<div class='tableauPlaceholder' id='viz1663717268981' style='position: relative'><noscript><a href='#'><img alt='Top Fiscal Years with Refugee Spots Left Unfilled from 1980-2022 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USRefugeeUnfilledSpots1980to2022_update&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='USRefugeeUnfilledSpots1980to2022_update&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USRefugeeUnfilledSpots1980to2022_update&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663717268981');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Design Note: I tried to figure out a way to trim the white space under my Tableau charts. A lot of clicking around and several Google searchs didn't yet lead me to the answer, but this is something I hope to fix in the future.
