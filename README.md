# <b> Theater Kickstarter Outcomes </b>

## <u>Overview of Project</u>
This is an analysis of Kickstarter campaign data from May 17, 2009 to March 15, 2017. Of most priority is to compare how theater, and specifically, play Kickstater campaigns performed. 

### Purpose
How do launch dates and funding goals affect the success rates of theater kickstarter campaigns? The purpose of this analysis is to compare how theater campaigns did based on the month the Kickstarter launched and how play campaigns fared based on their original Kickstarter goal. 

## <u>Analysis and Challenges</u>
The original data set contained 4,114 campaigns. 50 of the campaigns were live at the moment of data capture, so they were excluded from the analysis. Of those, 1,393 were under the parent category of "Theater" and 1,066 under the subcategory "plays". 

### Analysis of Outcomes Based on Launch Date
The data showed the launch date for each campaign. During analysis, these were separated into the individual months of campaign launch. One of the research questions is whether the month of launch makes a significant difference in the outcome of the project. The graph below shows the number of successful, failed, and canceled theater projects based on the month they were launched.  
<img width="800" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/116980760/200196458-41898913-7204-4ad9-82d6-308f8aeb3d8d.png">

### Analysis of Outcomes Based on Goals
The data showed the funding goals for each campaign. One of the research questions is how the Kickstarter goals impact success. The graph below shows the percentage of successful, failed, and canceled theater projects based on the funding goal.
<img width="800" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/116980760/200196468-267a0747-8d41-41a1-a62a-775fc2d0bcfb.png">

### Challenges and Difficulties Encountered

Some of the data was not in an user-friendly format. Dates originally had Unix timestamps and had to be converted to human-readable dates. Parent categories and subcategories were combined in one column and had to be separated for easier analysis. 



## <u>Results</u>

- May was by far the best month to launch a theater Kickstarter campaign. December is the worst month for theater campaign successes.

- The plays that had a funding goal under $15,000 and those between $35,000 and $45,000 were most successful, with a goal under $5,000 being the best probability of success. 

- Some topics in the dataset do not have adequate data points to draw educated conclusions. For example, there is not much project data on campaigns with goals over $15,000. The lack of data might lead to incorrect conclusions about funding goals. The data points for goals under $15,000 is over 10 times the number for those over $15,000. 

- A graph comparing average donation and funding success would be of interest. Also, comparing whether having the campaign being spotlighted had an impact on outcome.
