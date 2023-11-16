# Critique By Design 
To complete the "Critique By Design" assignment, I decided to focus on the dataset titled "NHTSA Recalls by Manufacturer." which features a pie chart displaying the total amount of recalls by the top 12 car manufacturers (assumingly in the United States and in the year 2022). I decided to critique this visual specifically because we have discussed pie charts a number of time throughout the course, particularly the point that pie charts should ideally not contain greater than about five variables. This visual immediately struck me as an easily remedied work, and one that I had ideas on how to better.  

The original visualization is the following: 
<iframe allow="geolocation" src="https://datahub.transportation.gov/dataset/NHTSA-Recalls-by-Manufacturer/mu99-t4jn/embed?width=800&height=600" width="800" height="600" style="border:0; padding: 0; margin: 0;"></iframe>

## Critique of the Visual 
Overall, there are a few things I believe the data visual does well. The pie chart provides adequate information that gives the viewer a comprehensive view of the data presented, allowing them to understand its importance. Unlike other examples seen in class and other assignments, the visual provides enough context to interpret the visual efficiently.

However, what stood out to me as inhibiting the chart’s ability to convey information in an intuitive manner was firstly color usage. Though the colors help a viewer to identify each manufacturer, it is difficult to understand the story the data is telling, and which points should be focused on when communicating the story. Several of the color variations are also similar hues to one another- for example the two shades of purple- that make for a less-than-ideal comparison when attempting to contrast the area of Daimler Trucks and Kia.

Secondly, I noticed the lack of context in what time periods these data points were taken from. What year is being measured? After looking at the chart below and some other areas of the visual, we can deduce the answer, but the knowledge was not intuitive when looking at the chart. In order to receive the whole data story, it is important for audiences to understand these key details.

In creating the visual differently, I would first utilize color in a more meaningful way, likley using it to highlight the top three most common manufacturers of recalls and developing a story there. The color usage would likely be shades of red with the rest of the pie chart in a shade of gray. This way, we still can see and understand each data point, but viewers are no longer overwhelmed with the color representing each data point and will know intuitively where to focus to receive key information.

If I were to take the critique in another direction, I may also consider re-creating the visualization in another format. As mentioned in the introduction, a pie chart is not an ideal visualization for a dataset that contains more than about five variables. Past this, the pie chart becomes cluttered, hard to analyze, and it is difficult for viewers to understand any kind of story being told with the data. Going off this point, it may prove beneficial to create a simple bar chart displaying the information. It would certainly tell a clearer story and would make it far easier to compare the totals of each car company.

As per the Stephen Few measuring/rating system for data visualizations, I rated the original visual out of ten in the following categories: 
Usefulness: 6
Completeness: 9 
Perceptibility: 4
Truthfulness: 9
Intuitiveness: 3
Aesthetics: 5
Engagement: 3

## Interviews 
### Interview 1: Male, 24
1) Can you tell me what you think this is?
   
"The amount of recalls each car manufacturer had in 2022."

2) Can you describe what this is telling you?
   
"It is telling me Ford and Crysler experience a lot of issues that need to be recalled by the manufacturer to be fixed, meaning the cars get sold with unsolved problems."

3) Is there anything you find surprising or confusing?
   
"The amounts in the chart, is that the total number of recalls sent out in 2022 or is it the amount of cars recalled? (such as each unit indicating thousands of cars)." 

4) Who do you think is the intended audience for this?
   
"I believe it’s intended to people interested in buying a car."

5) Is there anything you would change or do differently?
   
"I would clarify the data included. while I have an idea of what the number represents, I’m not 100% on what you’re trying to tell me. Including something like “each unit represents 1,000 cars” or clarifying the title would help with that."

### Interview 2: Female, 22
1) Can you tell me what you think this is?

2) Can you describe what this is telling you?

3) Is there anything you find surprising or confusing?

4) Who do you think is the intended audience for this?

5) Is there anything you would change or do differently?

## Feedback & Changes  
I changed a few of the mentioned topics from the interviewees, such as changing the color scheme around slightly. I also changed the numbers included, as per interviewee one's suggestion, to reflect the total amount of recalls rather than a simple number from 1-50 which is difficult to understand the significance of. 

I also received some helpful feedback in class from peers. They firstly agreed that a pie chart was not an appropriate or easily understood way to present the recall data. This confirmed my choice to instead display the data in the format of a bar chart. They then gave the feedback of instead of labeling the bars with the automotive manufacturer, to instead display the logo of the manufacturer above the bar. I liked this idea a lot, and were it not for my limitations in Tableau, I would have incorporated this idea into my final visualization. However, I am unsure of how to include such visuals in Tableau, and therefore stuck with the text labels on the X-Axis. 

# Final Visualization 
With the feedback in mind, I was able to create a final visual that incorporated both my critique of the original visualization as well as others' critique of my first drafts. 

### The final visualization is the following:  
<div class='tableauPlaceholder' id='viz1700097932480' style='position: relative'><noscript><a href='#'><img alt='&lt; 2022  NHTSA Recalls by Manufacturer&gt; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17000979170590&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_17000979170590&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17000979170590&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1700097932480');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>



