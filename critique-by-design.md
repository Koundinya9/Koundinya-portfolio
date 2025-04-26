| [Home Page](https://koundinya9.github.io/Koundinya-portfolio/) | [Visualising Government Debt](visualizing-government-debt.md) | [Critique and redesign (MakeoverMonday)](critique-by-design.md) | [Final Project I](final-project-part-one.md) | [Final Project II](final-project-part-two.md) | [Final Project III](final-project-part-three.md) |


# Precipitation Anomalies 

## Step one: the visualization

Link to the original visualisation(https://ourworldindata.org/grapher/global-precipitation-anomaly)


<img width="1327" alt="Screenshot 2025-04-02 at 9 00 04 PM" src="https://github.com/user-attachments/assets/2635d8bc-cb9b-4764-b0d7-9c5c039f1263" />

This is a data visualisation of the difference in a specific year's total precipitation — rain and snow — from the 1991–2020 average (the chosen threshold), measured in millimeters,
excluding fog and dew. Negative numbers indicate drier-than-average years.





## Step two: the critique


As seen in the image, this visualisation is very clunky, as you can only view the data of a few countries at a time. This makes it harder to compare the precipitation anomaly values of many countries. 

This type of visualisation also makes it harder for viewers to understand the climate of various regions around the world, as it can be hard for some users to correctly identify a country's location on the map. 

But, the filter for choosing the years is a good feature, and I have retained it in my redesign. It gives the user all the required information about each country, but a bar graph is not the right way to represent this type of data. 

## Step three: Sketch a solution

This is my initial sketch of a redesign :-

<div class='tableauPlaceholder' id='viz1743642292830' style='position: relative'><noscript><a href='#'><img alt='Deviation in Annual Precipitation compared to the 1991–2020 average (mm) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;InitialMakeOverMondayredesignsketch&#47;InitialPrecipitationMap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='InitialMakeOverMondayredesignsketch&#47;InitialPrecipitationMap' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;InitialMakeOverMondayredesignsketch&#47;InitialPrecipitationMap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1743642292830');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Firstly, I have changed the type of chart to a map. I have colour coded each country on the basis of the Avg. Precipitation Anomaly values, where blue represents a positive value and green represents a negative value.
This makes it very easy for users to understand how far away from the threshold all the countries are, at first glance. 
As mentioned above, I have retained the slider to choose the time period from range of years.

This representation makes it easier for users to compare the values of different countries, and also understand the climate patterns of different regions of the world in the last 70 years.

I have also 

## Step four: Test the solution


Questions to ask : 


- Can you describe to me what this is telling you?

- At first glance what do you think the colours represent ?

- What changes do you recommend ?


Results: 



| Question | Interview 1 | Interview 2 | Interview 3 |
|----------|-------------|-------------|
|Can you describe to me what this is telling you?    |It shows how annual precipitation has changed compared to past averages.              |Looks like a global map of rainfall deviations over time.             |It’s about changes in precipitation, but the numbers make it hard to read.             |
|At first glance what do you think the colours represent ?          |Green might mean more rain and blue less, but it’s not clear.             |It looks like changes in precipitation, but the shades are confusing.             |The colors show variation, but I can’t tell exactly what they mean.             |
|What changes do you recommend ?          |Remove the numbers to reduce clutter.             |The title should be clearer and more descriptive.             |Use a more intuitive color gradient.             |



Synthesis: 

From the feedback, I understood some flaws in my redesign and key changes that I need to make.

The colour pallet that I chose seems to be confusing. A blue-green pallet does not explain, at first glance, what is a positive value and what is a negative value.

The values on each country seem to be cluttered in some areas of the world, and they are also redundant, as they are being displayed anyways when we hover over each country. Also, the title is a little too wordy.

## Step five: build the solution

The final sketch of my redesign :-

<div class='tableauPlaceholder' id='viz1743643715578' style='position: relative'><noscript><a href='#'><img alt='Global Precipitation Change Relative to 1991–2020 Average (mm)This map shows the annual deviation in total precipitation (rain and snow) from the 1991–2020 average, called &quot;Precipitation Anomaly&quot;, measured in millimeters. Negative values indicate drier- ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalMakeOverMondayredesignsketch&#47;blueorangePrecipitationMap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FinalMakeOverMondayredesignsketch&#47;blueorangePrecipitationMap' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalMakeOverMondayredesignsketch&#47;blueorangePrecipitationMap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>       

<script type='text/javascript'>                  
  var divElement = document.getElementById('viz1743643715578');            
  var vizElement = divElement.getElementsByTagName('object')[0];    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';   
  var scriptElement = document.createElement('script');               
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';   
  vizElement.parentNode.insertBefore(scriptElement, vizElement);         
</script>




I have incorporated all the changes suggested to me in the survey. I have changed the colour pallet to Orange-Blue. This seems to explain the data better, as blue indicates a wetter place with a higher precipitation value (positive) and orange indicates a dryer atmosphere with a lower precipitation value (negative). This will allow users to quickly see which countries have a greater deviation from the threshold. 

The values on each of the countries are removed as they are anyways displayed on the tooltip when we hover over each of the countries. And the tooltip has also been redesigned to look more clean.

I have also changed the title and added a small description to explain the visualisation. This should allow the users to understand what the value means and give more context to the colours used.


This completes my redesign of the original visualisation.
