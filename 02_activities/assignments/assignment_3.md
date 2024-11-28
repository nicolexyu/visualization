# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Visualization: KPI Calcs Template
        
        Link: https://public.tableau.com/app/profile/andy.kriebel/viz/KPICalcsTemplate/Card

        Accessibility: 
        Accessibility for people with visual impairments or color blindness may be limited. This specific visualization does not appear to include alternative text or a high-contrast color palette.

        Reproducibility:
        The data source or calculation methods are not explicitly documented within the visualization, reproducibility is limited. Viewers may struggle to understand the data transformations or specific filters applied.

        Equity:
        Equity concerns arise if the data driving the KPIs reflect systemic biases (e.g., excluding underrepresented groups from the dataset or calculations). Without transparency about the source and scope of the data, it’s hard to assess how inclusive or equitable the visualization truly is.

        Visualization: Complaint Customer

        Link: https://public.tableau.com/app/profile/putra.gema.nusa7221/viz/complaint_customer/Dashboard1

        Accessibility: 
        The dashboard is red color theme. The reliance on color coding alone for differentiation may pose a challenge for users with color vision deficiencies (e.g., red-green colorblindness). For instance, important information conveyed through specific colors may not be equally perceptible to all viewers.

        Reproducibility:
        The dashboard does not explicitly document the source of the data, the calculation methods, or any assumptions made during the analysis. This lack of metadata limits reproducibility.

        Equity:
        Equity concerns can arise if the underlying dataset is incomplete, unrepresentative, or biased. For example, if complaints from certain demographic groups or regions are underreported, the visualization might not adequately represent all customer experiences.




        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Visualization: KPI Calcs Template

        Accessibility: 
        Use color schemes that are perceptible to users with color blindness. Add tooltips or text-based indicators to complement color-coded metrics. Ensure the visualization elements (e.g., charts, KPIs) are screen-reader compatible by adding alternative text descriptions for non-text elements.

        Reproducibility:
        Include a section or hover-over text that describes the data source, the time period covered, and any transformations or filters applied.

        Equity:
        Clearly state the dataset’s limitations and any excluded populations or categories to help users evaluate the data's fairness and representation.


        Visualization: Complaint Customer

        Accessibility: 
        Add alt text or descriptions for charts and visual elements so that screen readers can interpret the content. Provide a high-contrast color mode and avoid relying solely on color to differentiate data points. Include text-based indicators, such as labels or patterns, to enhance clarity.

        Reproducibility: 
        Clearly define the KPIs (e.g., total complaints, average response time) used in the visualization and ensure these definitions are transparent to users.

        Equity: 
        Include an equity analysis in the visualization itself, such as a breakdown of complaints by demographic or geographic group, to ensure fair representation and identify potential service gaps.
        Use additional charts to identify whether certain groups experience disproportionately high levels of complaints or slower resolution times, providing insights to address inequities in service delivery





        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
