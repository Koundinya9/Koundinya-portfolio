| [home page](https://koundinya9.github.io/Koundinya-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Assignment: [Visualizing Government Debt](visualizing-government-debt)


General Government Debt of countries in the year 2021 : ![Government Debt 2021](https://github.com/user-attachments/assets/1726ae66-4395-4649-9120-ec4814a0f586)
Source - Organization for Economic Co-operation and Development (OECD) -> [Link to the website](https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2021)





### Part 2 : Working with Tableau

Here, we are creating a heatmap that allows us to compare the government debt of various countries against each other. It also allows us to see how this value is changing over time in each country. By making it a heatmap, and setting the mid point, we can also see which countries are close to the mid point and those which are further away from it.



<div class='tableauPlaceholder' id='viz1742690615951' style='position: relative'><noscript><a href='#'><img alt='Government Debt Ratio ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRatio_17426901815850&#47;GovernmentDebtRatio&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebtRatio_17426901815850&#47;GovernmentDebtRatio' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRatio_17426901815850&#47;GovernmentDebtRatio&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                
           
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1742690615951');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement); 
</script>




### Part 3: Create your own visualization

In part 3, I created a bubble chart which shows the values of each country. I have also added a filter to select an appropriate year in which the viewer would like to see the data. I have also colour coded the data; countries with really high values are shaded with red and those with low values are blue.

This chart makes it easier for a viewer to immediately notice the countries that have the highest values in any given year, and also see those values by hovering over the countries. And if multiple years are selected then the values would be aggregated. 

As the chart in part 2 shows how the value of each country is changing over time, this chart helps us compare the values of each country against that of others.



<div class='tableauPlaceholder' id='viz1742694456528' style='position: relative'><noscript><a href='#'><img alt='Visualising Debt History of CountriesOECD. Accessed March 22, 2025. https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRatio_17426901815850&#47;VisualisingDebtHistoryofCountries&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebtRatio_17426901815850&#47;VisualisingDebtHistoryofCountries' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRatio_17426901815850&#47;VisualisingDebtHistoryofCountries&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                

<script type='text/javascript'>                    
           var divElement = document.getElementById('viz1742694456528');                    
           var vizElement = divElement.getElementsByTagName('object')[0];                    
           vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
           var scriptElement = document.createElement('script');                    
           scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
           vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
