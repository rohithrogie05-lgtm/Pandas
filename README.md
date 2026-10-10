TASK 8 :

This tree map shows the distribution of different departments such as IT, Sales, Operations, Marketing, Finance, and HR.
The size and color of each block represent the relative importance or value of each department.


task 11:
https://public.tableau.com/views/Task11_17907460735640/Sheet1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Five Business Insights

Mumbai and Pune have among the highest annual salary levels, indicating strong earning potential in these cities.

Chennai and Jaipur also show relatively high salary values, making them attractive locations for employees and businesses.

Bengaluru and Delhi fall in the medium-to-high salary range, suggesting competitive employment markets.

Hyderabad shows a moderate salary level, indicating a balance between employee earnings and potential business operating costs.

Kolkata has the comparatively lowest salary level in the visualization, which may indicate lower employee costs for businesses compared with the other cities.

Two Business Recommendations

Consider Mumbai, Pune, Chennai, and Jaipur for high-skilled talent recruitment where access to higher-paying and potentially more competitive talent markets is important.

Consider Hyderabad and Kolkata for cost-effective business expansion, especially for companies looking to control salary expenses while establishing operations in major cities.



TASK 12 ;

https://public.tableau.com/views/Task12_17916133434570/Sheet4?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

1 . visualizations minimum

Listing count by room type, split by superhost. Stacked bar. Replaces your Sheet 4.
Average price by superhost status and room type. Bar chart of AVG(realSum). Replaces your crosstab.
Price vs. distance from center. Scatter of dist against realSum, colored by room type. This is the strongest visual in this dataset.
Map of listings. lng and lat as the axes, colored by AVG(realSum).

2 . interactive filters

Filter 1: Room Type or Host Is Superhost. Right-click the filter, choose Apply to Worksheets → Selected Worksheets, and tick all four sheets.

Filter 2: a slider on dist or bedrooms, applied to all four sheets the same way.
Bonus action: in the dashboard, click the funnel icon on a sheet ("Use as Filter") so clicking a bar filters the others.
Layout: in your screenshot, Sheet 4 looks floating and overlaps the layout. Switch to a tiled layout, with the sheets in a 2×2 grid and the filters and legends in a right-hand container.


3 . interactive dashboard

I don't have your amsterdam_weekdays.csv contents, only the screenshot, so I built a working interactive dashboard that loads your CSV in the browser and calculates everything from it. That also means the findings come from your real data rather than from numbers I made up.


4 . key findings from the analysis

Finding 1: Superhosts are a minority, but score higher on satisfaction.
"Superhosts make up [X]% of listings. Their average guest satisfaction is [X] compared with [X] for non-superhosts, and their average price is €[X] versus €[X]."
Read from: Findings panel, first bullet. Set Filter 2 (Host type) to Superhosts and Non-superhosts to see the KPI cards for each group.

Finding 2: Room type is a major driver of price.
"Entire homes average €[X], which is [X]% higher than private rooms at €[X]."
Read from: Chart 2, or the second bullet in the Findings panel. Select each room type in Filter 1 and note the "Avg price" card.

Finding 3: Price falls as distance from the center rises.
"The correlation between distance and price is [X]. Listings within 2 km average €[X], versus €[X] beyond 2 km."
Read from: Chart 3 for the visual trend, and the third bullet in the Findings panel for the numbers.


5 .  suggestions/recommendations based on the findings

Based on Findings 1 and 2.
Superhosts are a minority of listings, and the data shows they score [higher / similar] on guest satisfaction ([X] vs [X]). A host with a high satisfaction score but no superhost badge is a clear candidate to pursue it. Before changing the nightly price, a host should compare it with the average for their room type (€[X] for entire homes, €[X] for private rooms), because room type explains more of the price than the badge does.

Recommendation 2: Investors and platform teams should focus on listings close to the city center.
Based on Finding 3.
Prices fall as distance from the center increases (correlation [X]), and listings within 2 km average €[X] against €[X] further out. For someone choosing where to buy or list a property, the center-adjacent band is where the data shows the strongest pricing. A platform team could use the same pattern to highlight or promote well-located, well-rated listings.


6 . overall conclusion based on the analysis

The analysis of Amsterdam's weekday Airbnb listings shows that price is shaped mainly by room type and by distance from the city center, while superhost status is linked to [higher / similar] guest satisfaction but is held by only a minority ([X]%) of hosts. Entire homes command a clear premium over private rooms (€[X] vs €[X]), and prices decline as listings move away from the center (correlation [X]). Together, these patterns suggest that hosts and investors get the most from choosing the right room type and location, and from building the guest ratings that lead to superhost status.

These results are correlations drawn from one city's weekday data. They don't prove that any single factor causes higher prices or ratings, and they may not hold on weekends or in other cities.
