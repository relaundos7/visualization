# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
        - Good: https://cdn.lifehack.org/wp-content/uploads/2015/04/infographic10.jpg 
        - Bad: https://dribbble.com/shots/21955628-Bar-chart-widgets-Hyper-charts-UI-Kit
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
        - Good: https://cdn.lifehack.org/wp-content/uploads/2015/04/infographic10.jpg (radar area chart)
            - Aesthetic: The composition is well-balanced, centred, and minimal—ample white space, neutral background, and typographic hierarchy (title > subtitle > axes labels).
            - Substantive quality: Each axis represents a clear category (e.g., hard work, education, connections, luck). The numeric data (percentages) are consistently plotted, maintaining integrity between values and graphical area.
            - Perceptual quality: The spatial and colour encoding leverages human perceptual strengths—seeing shape differences rather than decoding numbers. The consistent radial grid lines act as reference scaffolding, helping estimate relative magnitudes without cluttering with heavy grid text.
            - Accessibility and clarity: The contrast between colours and neutral background ensures legibility even for mild colour-vision differences. Because each group also differs by shape and outline, comprehension doesn’t rely solely on colour hue.
            - Advocacy: The design elicits reflection (“Poor need to change their life approach …”) while remaining grounded in survey data—showing data’s potential for insight and social commentary.
        - Bad: https://dribbble.com/shots/21955628-Bar-chart-widgets-Hyper-charts-UI-Kit (bar chart)
            - Aesthetic: The gradients don’t encode any additional variable — they’re purely decorative — which violates the principle of minimizing “non-data ink”. 
            - Substantive quality: The chart doesn’t clearly define what each bar represents — there are numeric labels on some bars but no visible axis titles, categories, or units.
            - Perceptual quality: The lack of grid lines or clear numerical axis makes quantitative comparison nearly impossible. You see “tall” vs “short” but not how much taller.
            - Accessibility: The neon blue/green palette against a black background looks appealing on high-end monitors but fails accessibility standards for users with low vision or colour-vision deficiencies.
            - Cognitive overload: Three different data summaries (Weekly, Monthly, Yearly) are shown in one graphic without clear explanation of their relationship. The viewer must mentally separate them, increasing cognitive load.
    - How could this data visualization have been improved?  
        - Good: https://cdn.lifehack.org/wp-content/uploads/2015/04/infographic10.jpg (radar area chart)
            - Quantitative precision: Exact values are readable only at node points; a small table or clearer radial scale could improve numeric accuracy.
            - Colour-blind verification: While hues contrast well, verifying with a simulator would confirm accessibility robustness.
        - Bad: https://dribbble.com/shots/21955628-Bar-chart-widgets-Hyper-charts-UI-Kit (bar chart)
            - Replace the neon gradient (blue → green glow) with a flat, consistent colour palette to enhance perceptual accuracy. 
            - Include x-axis labels and a y-axis with numberic scale to increase transparency.  
            - Separate weekly, monthly, and yearly comparisons into individual charts or use a dashboard layout where each time frame has its own consistent scale.

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
* Submission Due Date: `23:59 - 10/26/2025`
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
