What software did you use to create your data visualization?
I used Python, specifically the matplotlib.pyplot and seaborn libraries, to create the pie chart. Python was chosen because it offers powerful, reproducible, and customizable data visualization capabilities suitable for analyzing large datasets like the Apartment Building Registration file.

Who is your intended audience?
The intended audience includes Toronto city officials, fire safety regulators, tenants’ advocacy groups, and urban planners. This group is directly involved in assessing and ensuring residential safety standards and would benefit from quick insights into the level of fire safety compliance.

What information or message are you trying to convey with your visualization?
The pie chart communicates the proportion of buildings that have approved fire safety plans versus those that do not. The goal is to raise awareness about the current state of fire preparedness in Toronto's rental housing stock and identify potential areas for policy intervention.

What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
Design choices focused on clarity, balance, and color accessibility. I used the viridis color palette from Seaborn for colorblind-friendly tones, ensured equal aspect ratio for proper circle rendering, and included data labels (autopct) to display percentages directly on the chart for quick interpretation.

How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
Reproducibility was achieved by using a Python script, which includes the full data preparation and visualization code. Anyone with access to the dataset and Python can reproduce or update the chart, ensuring transparency and consistency even as the dataset evolves.

How did you ensure that your data visualization is accessible?
I used a colorblind-friendly palette, added percentage labels, and avoided over-segmentation to maintain readability. For screen reader users or alternative formats, the values from the pie chart can also be exported or presented as a table for easier access.

Who are the individuals and communities who might be impacted by your visualization?
Tenants living in high-rise or multi-unit residential buildings are the most directly impacted, especially those in buildings without approved safety plans. Additionally, fire departments, housing inspectors, and policy makers rely on this data to allocate resources and enforce regulations.

How did you choose which features of your chosen dataset to include or exclude from your visualization?
I selected only the APPROVED_FIRE_SAFETY_PLAN column because it directly answers a clear public safety question. Other features such as addresses or owner names were excluded to keep the visualization focused and avoid clutter or privacy issues.

What ‘underwater labour’ contributed to your final data visualization product?
Behind the final chart was significant work cleaning the dataset, handling missing or ambiguous values, filtering the relevant column, and choosing appropriate visualization settings like color schemes, labels, and formatting. This "invisible" work was crucial to producing a clear and effective visual summary.