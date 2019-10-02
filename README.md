# Data Visualization Project - Franchise Revenue

## Data
I propose to visualize [franchise revenue data](https://gist.github.com/vwm/1598b47bed8c5ecdd18dea2fb52680f4/#file-readme-md) for my project.  The dataset originates from R for Data Science's Tidy Tuesday weekly event for [July 2, 2019](https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-07-02).

This data shows the revenue of franchises by their media category (e.g., video games, merchandise, etc.), the original media source (e.g., book, film, etc.), the year the franchise was created, the franchise creator, and the current owner.

## Expected Behavior for Interactions
The visualization should show a chart whose X-axis, Y-axis, and color dimensions may be dynamically changed by the user by dropdown menus.  Depending on what is selected, the visualization should display the appropriate chart style: bar or scatterplot.

Upon clicking on a bar segment or scatterplot point, the visualization should display a second, linked chart that depicts the selected data in more detail.  For example, if a bar segment is selected that contains total revenue for a franchise, the linked chart should show a breakdown of the different types of revenue.

## Prototypes
I created an initial prototype which describes revenue by franchise.  It shows the top revenue items and puts franchise revenue into perspective based on media category.

It's already interesting to see how merchandise dominates the field. Marvel is the only franchise to appear high in the list from movie revenue, and Shonen Jump represents the highest contribution from the manga category.  This prototype highlighted how useful it would be to include dynamic axis and color selection.  It also led me to the idea of linking different chart types by clicking on bar segments.

[![image](https://user-images.githubusercontent.com/2779058/65630273-18306980-dfa3-11e9-933f-976104996302.png)](https://beta.vizhub.com/vwm/880af0e6afe24609b87ca5a18faa8a9e)

During the next round of development, I created a prototype that summarizes the total revenue of each franchise by the year it was created.  This prototype revealed the importance of understanding how to handle outliers and raised research questions involving finding more effective ways to present and organize the data under different dimensions.
[![image](https://user-images.githubusercontent.com/2779058/65630754-ff748380-dfa3-11e9-87f7-fbff2ea2b53b.png)](https://beta.vizhub.com/vwm/e99d07afaf75445b8edb3788056b8644)

## Questions & Tasks
These questions serve as a guideline and an inspiration for the visualization's design and interactive elements.  The visualization should provide the capability to answer these questions.
* How does revenue by revenue category change over time?
* How does the age of a franchise correlate with its total revenue?
* Is there a correlation between the original media type and the relative success of a franchise?
* Which franchise owners earn the most revenue for each media category?
* Which media categories are the most successful, and can any patterns be found to explain why?
* Are there interesting conclusions that may be reached regarding the original creator of each franchise?  

## Sketches
Here are some sketches created during project planning.

![image](https://user-images.githubusercontent.com/2779058/65631329-52026f80-dfa5-11e9-8e27-b4a571972155.png)


The right sketch is similar to the first prototype.  This stacked bar view would help reveal which factors impact revenue the most and see if any interesting patterns emerge across different dimensions.  An interactive, dynamic selection allows the user to select how to slice the data, making it easier to explore different thoughts and possibilities.

The left sketch is similar to the second prototype.  The goal is to use a spatial view to reveal if the original media source and a franchise's total revenue have a correlation.  Ultimately, linking these two chart types enables a user to evaluate global-level patterns while being able to investigate local-level details.

## Open Questions
I aim to address these questions as the visualization takes shape.
* How should the visualization take outliers into account for readability and visibility purposes?
* How should the visualization be coded or designed to dynamically change chart type?

## Schedule of Deliverables
This schedule estimates the delivery date of various aspects of the project.
* Week 7 - Recreate base visualizations using React and D3.
* Week 7 - Add calculated columns to the dataset for easier grouping and more varied visualization options.
* Week 7 - Implement dropdown menus for dynamic selections.
* Week 8 - Incorporate multiple chart types, showing a different one depending on what the user selects in the dropdown.
* Week 9 - Link the multiple chart types and display them at the same time (if the user clicks on a data point in one chart, it updates the display in the second chart).
* Week 10 - Add logic for automatically grouping and ungrouping data between the two linked charts.
* Week 10 - Polish all elements to make the visualization look professional and clean for final submission.
