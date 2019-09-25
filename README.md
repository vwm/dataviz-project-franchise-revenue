# Data Visualization - Project Proposal
This is a rough draft of a data visualization project proposal.



## Data
I propose to visualize [franchise revenue data](https://gist.github.com/vwm/1598b47bed8c5ecdd18dea2fb52680f4/#file-readme-md) for my project.  The dataset originates from R for Data Science's Tidy Tuesday weekly event for [July 2, 2019](https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-07-02).

This data shows the revenue of franchises by their media category (e.g., video games, merchandise, etc.), the original media source (e.g., book, film, etc.), the year the franchise was created, the franchise creator, and the current owner.



## Prototypes
I created an initial prototype which describes revenue by franchise.  It shows the top revenue items and puts franchise revenue into perspective based on media category.

It's already interesting to see how merchandise dominates the field. Marvel is the only franchise to appear high in the list from movie revenue, and Shonen Jump represents the highest contribution from the manga category.  My hope is to extend this view to allow dynamic selection of the x-axis category.

![image](https://user-images.githubusercontent.com/2779058/65630273-18306980-dfa3-11e9-933f-976104996302.png)



During the next round of development, I created a prototype that summarizes the total revenue of each franchise by the year it was created.  This prototyle revealed the importance of understanding how to handle outliers and raised research questions involving finding more effective ways to present and organize the data under different dimensions.
![image](https://user-images.githubusercontent.com/2779058/65630754-ff748380-dfa3-11e9-87f7-fbff2ea2b53b.png)



## Questions & Tasks
These initial questions are a guideline for the visualization's development path, and they may serve as implementation ideas.
* How does revenue by revenue category change over time?
* How does the age of a franchise correlate with its total revenue?
* Is there a correlation between the original media type and the relative success of a franchise?



## Sketches
...



## Open Questions
I'm considering several questions as the visualization takes shape.
* How can the user make informed dynamic choices on how to slice the visualization?
* How should the visualization take outliers into account for readability and visibility purposes?
* How will the visualization be managed to make it look polished (e.g., no truncated labels, properly formatted text and labels, etc.).
* How will the visualization simultaneously support and show different summaries of data (e.g., revenue by franchise category vs. total revenue by franchise).
