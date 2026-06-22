# Tableau Public Dashboard: https://public.tableau.com/views/DashboardDSI/Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# Visualization 2: Tableau Dashboard of Pre-Hospital Emergency Care Performance

Dataset: https://open.toronto.ca/dataset/pre-hospital-emergency-care-performance-metrics/

## What software did you use to create your data visualization?

I used Tableau Public to create a dashboard after using Python in a Jupyter notebook to clean the original dataset and export a Tableau-ready CSV.

## Who is your intended audience?

Anyone who might be interested in prehospital emergency care performance (city-specific) in Toront. (e.g., Toronto residents, city staff, public health researchers, and community organizations, emergency departments)

## What information or message are you trying to convey with your visualization?

The dashboard shows all three available metrics: emergency requests, emergency transport records, and arrival time to life-threatening calls. The message is that emergency-care performance should be viewed through both demand volume and time-based performance.

## What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?

I used separate charts because the dataset contains different units. Emergency requests and transport records are counts, while arrival time is measured in minutes. The dashboard uses a line chart for volume over time, a separate line chart for arrival time over time, and a horizontal bar chart for the latest-year volume comparison. I used clear titles, readable labels, tooltips, and a note explaining the difference between counts and minutes for accessibility. 

## How did you ensure that your data visualization is reproducible?

The Tableau dashboard is less fully reproducible than the Python chart because most layout and formatting choices are manual. To reduce this issue, I included the original dataset link, the cleaned CSV created in Python. I also saved or screenshotted the final dashboard image. I could have also done a screen recording while I was creating the viz, though I lacked resources and time to do it efficiently.

## How did you ensure that your data visualization is accessible?

I used clear chart titles, readable labels, tooltips, and separate charts for different units. I avoided relying only on colour by including metric names, values, chart titles, and explanatory text. I also included alt text for accessibility.

## Who are the individuals and communities who might be impacted by your visualization?

 The dashboard could shape how people in the health services arena as well as the general public understand emergency-care demand and public service pressure. This might also be useful for people who are working on care coordination across the patient care journey ( e.g., understanding the context in which prehospital services are operating).

## How did you choose which features of your chosen dataset to include or exclude?

I included metric type, year, value, value label, and unit because these fields to trend and comparison. I kept volume metrics and arrival-time metrics separate as comparing counts and minutes on the same axis would be confusing/misleading 

## What underwater labour contributed to your final data visualization product?

The dashboard depends on emergency service workers, dispatch systems, data collection processes

## Alt text

Dashboard showing Toronto pre-hospital emergency care performance from 2014 to 2025. One line chart shows emergency requests and transport records over time. A second line chart shows arrival time to life-threatening calls in minutes. A third horizontal bar chart compares the latest-year volume metrics.

