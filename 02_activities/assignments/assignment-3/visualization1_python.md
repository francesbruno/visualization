# Visualization 1: Emergency Requests and Transport Records Over Time

Dataset: https://open.toronto.ca/dataset/pre-hospital-emergency-care-performance-metrics/

## What software did you use to create your data visualization?

I used Python (3.11.14) in a Jupyter notebook \, with pandas for cleaning the data and Matplotlib for creating the chart.

## Who is your intended audience?
General population (Toronto residents, city staff, public health researchers) practically anyone interested in understanding emergency-care system demand.

## What information or message are you trying to convey with your visualization?

Compares emergency requests for service and emergency transport records from 2014 to 2025. The message is that pre-hospital emergency care can be understood partly through changes in service volume over time.

## What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?

I used a line chart because the data are organized by year, and the goal is to show change over time to match the message and data structure. Regarding formatting, I added a clear title, axis labels, a legend, gridlines, direct labels for the latest values, and a source note. These support readability and help the audience compare the two trends. Matplotlib plots as a figure containing axes, so I used that structure to customize the plot clearly.
## How did you ensure that your data visualization is reproducible?

I used the Toronto Open Data API to allow Jupyter notebook to download the data, clean it, create a cleaned CSV, and save the final PNG. I also included a notebook and requirements file. 

## How did you ensure that your data visualization is accessible?

Using readable text, clear axis labels, a legend, gridlines, and direct value labels. I did not rely only on colour because the lines are also identified through the legend and the latest values are written directly on the chart. Also included alt text.

## Who are the individuals and communities who might be impacted by your visualization?

Toronto residents, patients, caregivers, paramedics, prehospital services dispatch workers, city staff, and communities that rely heavily on emergency services.

## How did you choose which features of your chosen dataset to include or exclude?

I included year, emergency requests for service, and emergency transport records because they directly show system volume over time. I excluded the arrival-time metric from this chart because it uses a different unit of measurement, minutes instead of counts, and combining them would be misleading.

## What underwater labour contributed to your final data visualization product?

This visualization depends on the labour of paramedics, dispatch workers, data-entry staff, city open-data workers... 

## Alt text

Line chart comparing Toronto emergency requests for service and emergency transport records from 2014 to 2025. The x-axis shows year and the y-axis shows number of records. Two lines show the trends for requests and transports, with the latest values labeled directly on the chart.