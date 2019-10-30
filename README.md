# Data Visualization Project - Franchise Revenue

## Data
This project visualizes [franchise revenue data](https://gist.github.com/vwm/1598b47bed8c5ecdd18dea2fb52680f4/#file-readme-md).  The dataset originates from R for Data Science's Tidy Tuesday weekly event for [July 2, 2019](https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-07-02).

This data shows the revenue of franchises by their media category (e.g., video games, merchandise, etc.), the original media source (e.g., book, film, etc.), the year the franchise was created, the franchise creator, and the current owner.

## Visualizations
The project features two primary visualizations.  They are based off of the same core dataset, use a common color scheme, and provide distinctly different ways to view the same data.  As the visualizations took shape, various features were added to improve readability and polish, and the data was improved to provide alternative and generalized groupings.

The first visualization is a scatterplot that may show either category revenue (for a franchise's specific categories such as video games) or total revenue (across the entire franchise), selectable by dropdown. It also allows for selection of the color axis, describing data by the revenue category or the original media source.  Although this chart was designed to show a higher-level view, hovering over a data point displays the specific franchise.
[![image](https://user-images.githubusercontent.com/2779058/67864803-97621180-fafc-11e9-9ebe-b600b40c8a32.png)](https://beta.vizhub.com/vwm/b10862248c7b49458b927c4fef9010ae)

The second visualization is a stacked bar chart which shows total and category revenue simultaneously, this time placing a focus on the top 20 franchises as individual entities.  Revenue category is the common thread between the two visualizations, but this one places a greater emphasis on it, employing highlighting behavior to starkly show the most potent, driving factors behind revenue for the top franchises.
[![image](https://user-images.githubusercontent.com/2779058/67863120-af846180-faf9-11e9-812c-f1168e5be031.png)](https://beta.vizhub.com/vwm/649f76cf8fdf41f4ae26bea25b2fbac8)

## Interaction Behavior
The two visualizations feature different interaction styles.  The scatterplot allows the user to dynamically change the Y-axis and color-axis by dropdown menus.  Depending on what is selected, the visualization displays the appropriate data regarding revenue type or legend category.  The stacked bar chart allows the user to highlight segments of the chart by hovering over items in the legend.

## Prototypes
I created an initial prototype which describes revenue by franchise.  It shows the top revenue items and puts franchise revenue into perspective based on media category.

It was immediately interesting to see how merchandise dominates the field. Marvel is the only franchise to appear high in the list from movie revenue, and Shonen Jump represents the highest contribution from the manga category.  This prototype highlighted how useful it would be to include dynamic axis and color selection.
[![image](https://user-images.githubusercontent.com/2779058/65630273-18306980-dfa3-11e9-933f-976104996302.png)](https://beta.vizhub.com/vwm/880af0e6afe24609b87ca5a18faa8a9e)

During the next round of development, I created a prototype that summarizes the total revenue of each franchise by the year it was created.  This prototype revealed the importance of understanding how to handle outliers and raised research questions involving finding more effective ways to present and organize the data under different dimensions.
[![image](https://user-images.githubusercontent.com/2779058/65630754-ff748380-dfa3-11e9-87f7-fbff2ea2b53b.png)](https://beta.vizhub.com/vwm/e99d07afaf75445b8edb3788056b8644)

## Guiding Questions
These questions served as a guideline and an inspiration for the visualizations' design and interactive elements.  The visualizations are meant to provide the capability to answer these questions.
* How does revenue by revenue category change over time?
* How does the age of a franchise correlate with its total revenue?
* Is there a correlation between the original media type and the relative success of a franchise?
* Which media categories are the most successful, and can any patterns be found to explain why?

## Sketches
Here are some sketches created during project planning.

![image](https://user-images.githubusercontent.com/2779058/65631329-52026f80-dfa5-11e9-8e27-b4a571972155.png)


The right sketch is similar to the first prototype.  This stacked bar concept reveals which factors impact revenue the most and helps determine if any interesting patterns emerge across different dimensions.  An interactive, dynamic selection allows the user to select how to slice the data, making it easier to explore different thoughts and possibilities.

The left sketch is similar to the second prototype.  A spatial view helps show if the original media source and a franchise's total revenue have a correlation.  Ultimately, these two chart types enable a user to evaluate global-level patterns while being able to investigate local-level details.

## Future Work
Link or combine the two visualizations into one visualization with two cohesive views.
