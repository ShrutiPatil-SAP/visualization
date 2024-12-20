# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify:

   Visualization 1: COVID-19 Case Trends Over Time
  Link: https://data.ontario.ca/dataset/status-of-covid-19-cases-in-ontario

  > What software did you use to create your data visualization?
     Python (matplotlib and seaborn). Python provides flexibility and precision in creating time-series visualizations. Libraries like matplotlib and 
     seaborn are ideal for detailed trend analysis.

   > Who is your intended audience?
   Policymakers, health officials, and researchers aiming to monitor infection trends and evaluate intervention effectiveness.
    
    > What information or message are you trying to convey with your visualization? 
    Showcase daily and cumulative case trends to highlight peaks and plateaus, assisting in evaluating the progression and control of the pandemic.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
1) Substantive: Focused on essential metrics such as daily cases and 7-day rolling averages.
2) Perceptual: Smooth curves and clear legends for trend clarity.
3) Aesthetic: Use of contrasting colors to differentiate trends (e.g., daily vs. cumulative cases).
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Code is included with comments, and the dataset is publicly accessible. This ensures reproducibility for similar studies.
   
    > How did you ensure that your data visualization is accessible?  
     Annotations on peaks and significant events improve comprehension. Colorblind-friendly palettes ensure inclusivity.

    > Who are the individuals and communities who might be impacted by your visualization?  
    The visualization helps communities globally understand the effectiveness of public health measures and the importance of compliance during spikes.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Focused on case counts, excluding unrelated fields like administrative codes.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Cleaning data to handle missing dates and calculating rolling averages.

    Visualization 2: Vaccination Rates by Region
   Link: https://data.ontario.ca/dataset/covid-19-vaccine-data-in-ontario
   > What software did you use to create your data visualization?
   Tableau Public
   > Who is your intended audience?
   General public, health planners, and community organizations interested in regional vaccination disparities.

> What information or message are you trying to convey with your visualization?
   Highlight regional differences in vaccination rates, identifying areas with lower coverage to guide outreach and policy.

> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
Substantive: Focused on vaccination rates by region and total population.
Perceptual: Consistent scaling for all regions; clear legend for interpretation.
Aesthetic: Balanced color gradients (e.g., shades of green) to represent vaccination levels.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
Tableau files and the dataset link will be shared, but Tableau's interactivity is less script-reproducible compared to Python.

> How did you ensure that your data visualization is accessible?
Tooltips on hover include text descriptions for each region. Contrasting colors ensure readability for colorblind users.

Who are the individuals and communities who might be impacted by your visualization?
Identifying under-vaccinated areas allows targeted outreach to improve health outcomes.

> How did you choose which features of your chosen dataset to include or exclude from your visualization?
Focused on regions, vaccination percentages, and population; omitted unrelated fields like administrative regions.

> What ‘underwater labour’ contributed to your final data visualization product?
Aggregating data by region and ensuring uniform vaccination percentage calculations.






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
