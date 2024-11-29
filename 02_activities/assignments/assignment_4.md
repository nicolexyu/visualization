# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

    Note: Please refer to the folder for detail information. 
    
    [Short-Term Rentals Analysis](https://github.com/nicolexyu/projects/tree/main/Short-Term%20Rentals%20Analysis)

    [Project Overview](https://github.com/nicolexyu/projects/blob/main/Short-Term%20Rentals%20Analysis/Project%20Overview.md)
    
    [Data folder](https://github.com/nicolexyu/projects/tree/main/Short-Term%20Rentals%20Analysis/data)

    [Python Code](https://github.com/nicolexyu/projects/blob/main/Short-Term%20Rentals%20Analysis/Python%20code.ipynb)


    > Python

    > What software did you use to create your data visualization?

    The visualizations were created using Python, specifically using libraries such as Matplotlib and Seaborn.

    > Who is your intended audience? 

    The intended audience includes:

    - Researchers and analysts studying the distribution and types of short-term rentals.
    - Community members seeking transparency in rental property statistics.
    - Real estate professionals interested in market trends for short-term rentals.
    
    > What information or message are you trying to convey with your visualization? 
    The data visualizations highlight:

    - The distribution of property types used for short-term rentals.
    - Wards with the highest and lowest numbers of short-term rental properties.
    - How property types are distributed across wards.
    
    These insights reveal key trends in rental housing and provide a basis for understanding geographic and property-type preferences.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 

    Substantive Principles:
    Focused on clarity and relevance, ensuring the charts answer specific questions about the dataset.

    Perceptual Principles:
    Used bar charts for categorical comparisons (e.g., property types, wards), which are easily understood by viewers.

    Aesthetic Principles:
    Ensured charts have a clean layout with readable axis labels and titles, such as “Count of Short-Term Rental Properties by Type.”
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    Python: Scripts for data cleaning, analysis, and visualization are documented and can be reused by others with the dataset.
    
    > How did you ensure that your data visualization is accessible?  

    Python Visualizations: Titles, axis labels, and annotations make the data easily interpretable. A high-contrast color palette was used for readability.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    Positively Impacted:
    - Policy-makers and planners can use the insights for housing regulations and planning.
    - Community members gain transparency in local housing trends.

    Potentially Negatively Impacted:
    - Property owners in wards with high concentrations of rentals may face increased scrutiny or regulation.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    Included Features:

    - Property Type: Central to understanding the distribution of short-term rentals based on the type of property.
    - Ward Name and Ward Number: Essential for geographic analysis of property distributions across the city.
    - Counts: Used to show the frequency of properties for each category, providing quantitative insights.

    Excluded Features:

    - Unit Numbers: These were excluded because they were not critical to understanding rental distribution trends.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Data Cleaning: 

    Unit Column: Missing values in the unit column were left as is since the absence of unit numbers does not affect the analysis of property types or ward distributions.

    Ward Number and Ward Name Columns: Rows with missing values in these critical columns were dropped to maintain data quality for analyses and visualizations involving geographic or ward-based attributes. Since there were only 4 missing values, this represents a negligible portion of the dataset and does not impact the overall analysis.

    Data Transformation:

    Aggregated the data by ward and property type to generate meaningful insights for visualizations.

    Visualization Design:

    Iterated on chart types and layouts to ensure that the plots effectively communicated the key insights.




    > Tableau
    
    > What software did you use to create your data visualization?

    Tableau Public was utilized to create the interactive dashboard available at the link: 
    https://public.tableau.com/app/profile/n.y8309/viz/DashboardShort-TermRental/DashboardShort-TermRental?publish=yes

    > Who is your intended audience? 

    - Researchers and analysts studying the distribution and types of short-term rentals.
    - Community members seeking transparency in rental property statistics.
    - Real estate professionals interested in market trends for short-term rentals.

    > What information or message are you trying to convey with your visualization? 

    - The distribution of property types used for short-term rentals.
    - Wards with the highest and lowest numbers of short-term rental properties.
    - How property types are distributed across wards.
    
    These insights reveal key trends in rental housing and provide a basis for understanding geographic and property-type preferences.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 

    Substantive Principles:
    Focused on key dimensions (e.g., ward, property type) to maintain relevance and align with stakeholder needs.

    Perceptual Principles:
    Interactive filters and tooltips make complex data accessible to diverse audiences.

    Aesthetic Principles:
    Utilized a professional color scheme that aligns with Tableau's default palettes but is adjusted for accessibility (e.g., avoiding colors that are hard to differentiate for color-blind users).
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    Tableau: The dashboard is published on Tableau Public, ensuring accessibility and transparency, though it is less directly reproducible compared to Python code.
    
    > How did you ensure that your data visualization is accessible?  

    Tableau Dashboard: Interactive features allow users to explore the data by property type and ward, accommodating varying interests and analytical needs.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    Positively Impacted:
    - Policy-makers and planners can use the insights for housing regulations and planning.
    - Community members gain transparency in local housing trends.

    Potentially Negatively Impacted:
    - Property owners in wards with high concentrations of rentals may face increased scrutiny or regulation.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    Included Features:

    - Property Type and Ward: Key variables that provide a detailed understanding of the geographic and categorical distribution of short-term rentals.
    - Filters: Added to enable users to explore the data dynamically.

    Excluded Features:

    - Unit Numbers: Excluded for the same reasons as in Python, as they were not relevant to the visualizations or analysis.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Data Preparation for Tableau:

    Exported a cleaned and aggregated dataset compatible with Tableau, ensuring proper column formats and no missing critical values.

    Dashboard Design:

    Experimented with multiple layouts to ensure the visualizations were user-friendly and intuitive.
    
    Set up filters for interactivity and tested their functionality to ensure no errors.

    Color and Accessibility Optimization:

    Customized Tableau’s color palettes for readability and accessibility, accounting for potential color blindness.

    Testing and Iteration:

    Tested the dashboard in Tableau Public to ensure performance and functionality for public viewing.





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
