| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
Redesigning World Steel Production Data

## Step one: the visualization

[World Crude Steel Production](https://worldsteel.org/data/world-steel-in-figures/world-steel-in-figures-2025/)

I chose the World Crude Steel Production data set because I did my summer internship with The Breathe Project, an air quality nonprofit serving the SWPA region, and I learned a lot about the harms of the Steel Industry. When I looked through the different figures, I realized that this page was targeted towards those interested in the investment in the steel industry and steel production. I thought it would be interesting to look at this data from a different perspective than the one that I was used to with my internship. 

The figures held so much information about the history of the global steel industry, but it was missing a clear, cohesive story. 

## Step two: the critique

For this data set, I think there was a missed opportunity to tell a really interesting story about the World Steel Production. My first takeaway from the different data visualization types in this set is that there is a heavy reliance on tables to show world crude steel production from the 1950s to 2024, the growth rates over that time period, and which companies and countries are producing the most steel. While the use of the tables are useful, complete, and intuitive, it is missing the opportunity to be aesthetically pleasing and really capture the engagement of the viewer. In the set, some of the tables are shown along with a line graph to show the data in a more complete way. This makes the overall dashboard more cluttered, less intuitive, and affects the perceptibility because the viewer could get confused and wonder if there is a difference between the two data viz figures. One of the figures is a bar graph to show crude steel production from 2000-2024. The bars are represented through steel cylinder rods. I like that this narrows the time frame for the viewer because it provides a more structured approach to the data, improving the usefulness and intuitiveness. I like the attempt to lean into the aesthetics and engagement portion of the visual but the cylinders might not be the right tool to do that in my opinion. In this figure from 2020-2024, the steel production value is relatively the same, but the cylinders vary in size and some cylinders appear smaller than subsequent year’s cylinders even though their value of steel production is higher. This makes it less truthful. Additionally, the takeaway from this figure is that steel production has been stable since 2020 and that is stated in a sentence at the bottom of the figure. This is not very useful or aesthetically pleasing.

I believe the primary audience for this data visualization set is potential investors in the steel industry. The target audience is also definitely those familiar with the steel industry due to the use of certain terminology like 'tonnage'. This would make the most sense because the overall message is the sustained growth in steel production and that this is likely to remain unchanged. You can also learn what companies and countries produce the most steel. I do not think this visualization is effective for reaching this audience because while it is complete, it is not very engaging and portions are not very intuitive. 

I plan to focus on creating a dashboard that shows the growth of the steel industry with a specific focus on the steady amount of steel production in the last four years. I am going to do so by redesigning the bar graph and tables. My main ideas are for the bar graph to put a more obvious emphasis on the years 2020-2024 through colors and sizes and not rely on text in the graph. The tables can be portrayed in line graphs or tree maps to have a bit of context for the magnitude. 


## Step three: Sketch a solution

[Sketch.pdf](https://github.com/user-attachments/files/22417460/Sketch.pdf)

## Step four: Test the solution

Results: 

Questions and Interview Responses                                 
------------------------------------

Can you describe what this is telling you?

Student one said it is obviously about steel production in the world, but they were confused on the relivance of each graph to each other. 
Student two agreed. 

What do you find confusing?

Student one said the time frames are all different and there does not seem to be any method for determining which graph shows which timeframe. 
Student two did not understand why certain bars were highlighted and the others were not.

What would you do differently?

Student one suggested including landguage to describe the dashboard as a steel production post-covid dashboard and use language like 'in the last decade'. 
Student two recommended that if I wanted to include a figure for weight per capita and something to contextualize that, that I should compare the weight to average human weight. 

Synthesis: 

The feedback let me know that my dashboard was not as clear as I thought it would be. The most common critic I recieved was about more intentiaonal language in my titles and more intentional labeling methods. After the feedback session, I realized I wanted to incorporate more about steel production from each country as a part of the total make up and take an angle of where the U.S. falls on that list. 

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1758244606742' style='position: relative'><noscript><a href='#'><img alt='Reinvestment in the U.S. Industry comes at a relatively stable and high period of Global Steel Production. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldSteelProductionRedesignAssignment&#47;Redesign&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='WorldSteelProductionRedesignAssignment&#47;Redesign' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldSteelProductionRedesignAssignment&#47;Redesign&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>     

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758244606742');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='977px';}                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>

When I went to do the final resdesign, I discovered that the data source available was a much smaller set of data than what I had planned for. The data set only included the steel production for each steel producing country in 2024 and an estimate for the total in 2025. This changed the way that I approached my dashboard because the story of the history of the steel industry (dating back to 1950) could no longer be told. Instead, I chose to tell a story for an audience that is interested in the U.S. Government's interest and reinvestment in the steel industry this year. To do this I made a dashboard with three figures. The first was a bar chart showing the top 15 steel producing countries in 2024, showing that the U.S. ranks fourth. The second was a bar chart showing the total global production of steel in 2024 and 2025, highlighting that the steel production is high and stable. The third was two line graphs to show that the rankings of global steel production from 2024-2025 have remained relatively unchanged. The story I was trying to tell is that there is value in the U.S. reinvesting in the steel industry because globally, steel production is still high and the U.S. has room to be a larger contributor. This was an interesting exercise for me because I do not agree with the reinvestment into the Steel Industry, but from this perspective it can be a different story. 

## References
[Source](https://worldsteel.org/data/world-steel-in-figures/world-steel-in-figures-2025/#world-crude-steel-production-1950-to-2024)

## AI acknowledgements
N/A

