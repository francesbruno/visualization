# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Your answer...
      

A. Good visualization: https://public.tableau.com/app/profile/iaroslava/viz/FinancialConsumerComplaintsDashboard_17718710866110/Overview

I classify the interactive dashboard “Financial Consumer Complaints” as a good data visualization. The dashboard is effective because it presents the data at multiple levels: an overview page, an analysis page, and a detailed records page. The Overview page summarizes January–December 2016 complaints using KPI cards, a monthly trend line, donut charts, a state map, and a product comparison chart. It shows 7.2K total complaints, a 93.5% timely response rate, a 17.9% dispute rate, and a 14.8% relief rate. Because it is interactive, we can press KPI cards, filter by product, and hover over states to see more details.

1. The dashboard has strong substantive qualities because it clearly presents important summary measures. The Overview page starts with high-level KPI cards, then moves into more specific views such as complaints over time, complaints by state, and complaints by product. This helps us understand the overall complaint situation before looking at more detailed charts. The dashboard also compares 2016 data with the same period in 2015, which supports a more meaningful interpretation than showing 2016 alone.

2. the visualization uses appropriate chart types for different kinds of data. The line chart is useful for comparing monthly complaint trends between 2016 and the same period in 2015. The state map supports geographic comparison, while the horizontal bar chart makes it easy to compare complaints and timely response rates by product. The Analysis page adds deeper views, such as dispute rate by intake lag, top risk drivers by sub-product, company response by channel, a bubble chart for channel quality versus risk, and a heat map of complaint volume by issue and channel. These views allow us to move from summary to deep dives.

3. the dashboard has strong perceptual qualities because the layout separates information into clear sections. We can move from high-level KPI cards to deeper trend, geography, product, issue, and channel details. This supports storytelling because the dashboard shows not only the number of complaints, but also when complaints changed, where they were concentrated, and which products were involved. The Details page also provides a table of individual complaints, including submission date, state, product, issue, submission channel, timely response, consumer disputed status, and company response. This improves transparency because we can inspect the records behind the summary charts.

4. A few points for improvement: First, some labels and legends should be larger and higher contrast, especially because the dark background makes small labels harder to read. This would improve accessibility and reduce cognitive load. Second, abbreviations such as SP, SPLY, and TR Rate should be defined directly on the dashboard. These terms may be familiar to the designer, but unclear to a general audience. Adding short definitions would make the dashboard easier to understand.


B. Bad visualization: https://public.tableau.com/app/profile/muhammad.zaid5165/viz/FinancialConsumerComplaintsPractice/Sheet9

I classify “Financial Consumer Complaints Practice” as a bad data visualization. The workbook uses consumer complaints data, but the individual sheets do not communicate a clear story or work together as an effective dashboard. Instead, we see disconnected charts, tables, maps, and summary cards that are difficult to interpret as one coherent analysis, which weakens storytelling.

1. The visualization has weak perceptual qualities because the main message is unclear. Several sheet titles are very long, such as “Average Gap in Number of Days Between Complaints Submitted and Complaint Received for the Post Mail.” This makes the chart harder to understand before we even look at the data. Other views, such as the pie chart for “Number of Consumer Dispute Out of Timely Closed Complaints,” have overlapping labels and too much empty space, making the result visually confusing.

2. The visualization has weak aesthetic qualities because the design is inconsistent across sheets. Some charts use blue gradients, another uses orange and red, and others use pale map colors or table formatting. The font sizes, spacing, and layouts also vary widely. This increases cognitive load because we have to repeatedly relearn how to read each view instead of following a consistent design system.

3. Some chart choices are not appropriate for the data. The pie chart comparing N/A, No, and Yes dispute categories is difficult to interpret because slices are harder to compare accurately. A sorted bar chart would make the differences clearer. The “Popular Year for Complaints Related to Vehicle loan or lease” chart uses very large square marks for only four yearly values, creating excessive whitespace. A simple bar chart would compare the years more efficiently, while a line chart would better show change over time. The state-wise credit card complaints map provides geographic context, but it takes up a large amount of space and makes smaller states hard to compare. A ranked bar chart of top states, or a map paired with a table of exact counts, would be clearer. The workbook also relies heavily on tables, such as the mortgage issues table and the unresolved complaints table. Tables are useful for lookup, but they are weaker for showing patterns. The unresolved complaints table could be improved with a bar chart showing maximum and minimum days passed by product.

4. 2 major points for improvement. First, the workbook should be redesigned as a single organized dashboard with a clear title, short subtitles, and grouped sections such as complaint volume, complaint status, product type, and geography. Second, the chart types should be simplified by using bar charts for category comparison, line charts for time trends, and maps only when geography is central. These changes would improve perceptual clarity, reduce cognitive load, and make the data easier to compare accurately.


      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
