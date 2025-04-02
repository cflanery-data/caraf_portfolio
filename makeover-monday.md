# Assignment: Critique and Re-Design (Makeover Monday)

[Makeover Monday](https://makeovermonday.co.uk/) is a website that has links to data visualizations with public data that you can use to practice critiquing and redesigning data visualizations. 

## Step One: Choose a data visualization from Makeover Monday.
For this assignment, I have chosen to redesign this data visualization, titled: [Mushroom is the UK's most liked pizza topping](https://yougov.co.uk/politics/articles/17714-does-pineapple-belong-pizza). After looking through many of the listed data visualizations on the Makeover Monday website, I ultimately decided to go with this one, primarily because I had a lot to say about it. I thought it was a fun topic, and the picture of the pizza drew me in. I also liked the context of the article. As a hater of pineapple on pizza myself, I was interested in seeing what the UK had to say about it. I was most confused by the slices of the pizza being evenly sliced, leading me to think I was looking at a pie graph, when the slices of the pizza had nothing to do with the data proportions. This is what I most wanted to change in my redesign. 

## Step Two: Critique the data visualization.
The next part of the assignment required using Stephen Few's [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) as a template to critique the original viz. 

I struggled a lot with this critique. I felt that the context of the article was discussing whether pineapple on pizza was liked, yet the data visualization merely told us that mushrooms were the most liked topping in the UK. I thought a lot about what the difference between "Perceptibility" and "Intuitiveness" was and ultimately settled on the graph being low in perceptibility and high in intuitiveness. This means that the information was unclear and difficult to parse (perception) because of the pie graph hallucination as mentioned before along with no clear focus on mushrooms being the most liked pizza topping, yet it is familiar to a common viewer and doesn't take too much effort to understand in terms of being able to figure it out fairly quickly. I was also confused by the note at the bottom: why omit eight more toppings from the data visualization, especially ones that are ranked highly? I was drawn in by the pizza image, but I felt that the slices were too confusing at a glance and wanted to work on trying to bring the fun pizza feel to my redesign, while making it easier to read. 

## Step Three: Sketch out a solution.
I decided to just go ahead and use Tableau for my draft design. I knew I wanted to do a horizontal bar chart since I thought that would best be able to show all the toppings (even the ones that were omitted from the original graph). I tried to do a pizza color theme but wanted to emphasize UK respondants liking pineapple on pizza as being the main takeaway rather than just most liked toppings. I changed the title to emphasize this instead of showing mushrooms as the most popular topping. 

Here was my first draft: 
![Pineapple on Pizza Draft 1](https://github.com/user-attachments/assets/2a441f1e-979f-474b-9ed8-140a26781f3f)

## Step Four: Test the solution. 
I interviewed a friend, mid-20s, that visited me for the weekend, who has had very little experience with critiquing data visualizations. She was able to get the gist quickly, that people in the UK like pineapple on pizza; however, she wasn't a big fan of the colors. Taking this feedback, I made my second draft: 
![Pineapple on Pizza Draft 2](https://github.com/user-attachments/assets/dbe55e80-3ddf-4b60-825e-9435a7fb1863)

I changed the colors to be gray and yellow-orange to match the pineapple color and still make it stand out. Even though I lost a bit of the "pizza" color scheme, I felt the colors worked better, especially for pineapple. This version is the one I took to class. There, I got feedback from three other students in our Telling Stories with Data class, mid-20s. The general feedback from the three of them was that while pineapple on pizza was coming across, the topic seemed like it was fun and for the general public, not necessarily corporate. If I could make the fonts more fun and play around with colors rather than gray, it'd be more engaging. They also were a bit confused if the graph was showing the UK's most _liked_ toppings or _favorite_ topics, so I changed the subtitle to match the title. 

Synthesis: 

| Question | Interview 1 | Group Class Interview |
|----------|-------------|-------------|
| Can you tell me what you think this is? | Graph of pizza toppings. | UK citizens like pineapple on pizza. |
| Who do you think is the intended audience for this? | Corporate/business. | UK businesses? |
| Is there anything you would change or do differently? | Colors | Making it more fun with color and fonts. |

As you can see, most people were able to easily see what the graph was trying to portray; however, they thought it should be more fun instead of corporate-looking, and thought this was most easily done through the use of color. 

## Step Five: Build your solution.
Based on everyone's feedback, this is the final redesign: 
![Pineapple on Pizza Redesign](https://github.com/user-attachments/assets/40cb4a5b-6d36-4270-9dc9-96a9d9b536fa)

I wanted to highlight the UK's liking of pineapple on pizza. The original graph was a list of the most liked toppings in the UK, but I felt the data visualization didn't mix well with the content of the article, as it was discussing specifically pineapple as a topping. The original viz was also giving the impression of a pie graph when the percentages were not proportions of a whole. Thus, I wanted to do a bar graph to be able to show each topping compared with each other. 

Color was the hardest area for me. I wanted to make it fun but also make it easy to see the pineapple. I eventually added a column to my data: Fruit, Fish, Meat, and Vegetables and categorized each item according to those. This allowed me to add a legend to the side with each category. I chose to use categorical colors for these: Blue for Fish, Red for Meat, Green for Vegetables, and Pink for Fruit. I made those colors very lightly saturated so they don't distract from brightly saturated pineapple yellow, which I separated out in the legend and moved to the top for more visibility. Even though pineapple being on the top is not in order of percentages, the eye is immediately drawn to the first line due to the bright color and according to reading conventions. 

I also wanted to make it more fun and less corporate, as this data would not necessarily be used in a business setting. Rather, to me, the audience would be a general population UK resident looking for validation about their pineapple on pizza usage. Therefore, I added iconography to the labels on the y-axis, and I also made the font of the title and subtitle more fun. In addition, I changed the subtitle to match the title by emphasizing _most liked_ instead of _favorite_.  

Overall, this assignment was really fun to do, and I'm happy with the result. I would love to hear your thoughts! 

Embedded Result for Interaction: 
<div class='tableauPlaceholder' id='viz1743613522461' style='position: relative'><noscript><a href='#'><img alt='Nearly Half of the UK Likes Pineapple on PizzaSurvey shows the UK’s most liked pizza toppings — pineapple included.Source: Smith, M. (2017, March 6). Does pineapple belong on a pizza? | YouGov. Does Pineapple Belong on a Pizza? https:&#47;&#47;yougov.co.uk&#47;pol ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pi&#47;PineappleonPizza_17436089327090&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='PineappleonPizza_17436089327090&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pi&#47;PineappleonPizza_17436089327090&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1743613522461');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);       </script>




Here is a link to the final visualization on Tableau Public too!
[Pineapple on Pizza Redesign](https://public.tableau.com/app/profile/cara.flanery/viz/PineappleonPizza_17436089327090/Sheet1?publish=yes)

## References
Few, S. (2017). Data Visualization Effectiveness Profile. Perceptual Edge. 

Smith, M. (2017, March 6). Does pineapple belong on a pizza? YouGov. Does Pineapple Belong on a Pizza? https://yougov.co.uk/politics/articles/17714-does-pineapple-belong-pizza



