# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
1. Python (see Assignment 4 Juypter Notebook)
2. Google Sheets. Link: https://docs.google.com/spreadsheets/d/1O3spCiv5rvNFqaLiYVoVTVwQv07STX_3c6jO5-oNfFo/edit?usp=sharing
    > Who is your intended audience? 
    Anyone interested in knowing the Egg Production capacity in Canada.
    > What information or message are you trying to convey with your visualization? 
    That the production of eggs has grown over time, driven by both an increase in layers and an increase in # of Eggs produced per layer.
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
- Made a chart that communicated the trend as simply as possible. 
- Ensuring that tooltips were available if precise values were needed.
- Google Sheets allowed for displaying of Raw Dataset given how clean it was for those preferring to look at a table of numbers.

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    1. Produced notes on data cleaning of the xlsx to CSV file
    - Produced comments on how to get packages, what lines of code were doing, why I chose to make certain decisions.
    2. Used the least amount of edits on Google Drive to make it easy to reproduce. Included notes on separate sheet. Used Google Sheets because Software was accessible for reproducibility on graphs. However it is susceptable to updates changing the layouts/process to generate the same layout.
    > How did you ensure that your data visualization is accessible?  
    - Tried to ensure visibility from colour blindness by ensuring darkness difference between lines in the same graph.
    - I would publish with a link to Ontario's data catalog for users to get more information on how data was collected and what they mean. (See Citation Section)

    > Who are the individuals and communities who might be impacted by your visualization?  
    - The egg farmers and their communities as it pertains to the industry's scale and production.
    - Probably any retailers to understand if there is a gap in supply from farmers and demand from customers around Ontario.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    - Dataset was simple, and thus all metrics were included as it was deemed they had value and easy to display.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    - Sourcing the dataset from the Ontario Open Datasets
    - Cleaned data to push into plotly express


Citation of Data Source: 
Agriculture, Food and Rural Affairs. (n.d.). Ontario Egg production. Ontario egg production. https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fdata.ontario.ca%2Fdataset%2F5fc7016b-0c85-4016-8e3f-14c8a13d2158%2Fresource%2F122eed63-7035-41bb-a246-23aaf3f63014%2Fdownload%2Feggs.xlsx&wdOrigin=BROWSELINK 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
