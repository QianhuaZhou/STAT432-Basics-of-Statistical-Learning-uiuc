- [5 Points, 1 page]

  Project Description and Abstract:

  - Provide a concise summary of your project, including its goal, approach, and key findings, similar to an abstract.
  - Briefly mention any unique or specialized methods used in your analysis, especially if they extend beyond the techniques covered in this course. Explain how these methods differ from those reviewed in the Literature Review section.
  - Include the names of all team members and their NetIDs.
  - Provide a brief statement of AI usage in your project. For example, was any AI tool used in competing the code, correcting grammar errors, etc.? You should be aware that some behaviors are prohibited by the university’s academic integrity policy. For a general guideline, I would refer to [this statement by Elsevier](https://www.elsevier.com/about/policies-and-standards/generative-ai-policies-for-journals).

- [10 Points, 1 page]

  Literature Review

  - Use Google Scholar to find research papers on used car price prediction, noting that these studies may use different datasets.
  - Summarize the main findings and approaches from at least two selected papers. Provide full citations and URLs for each paper.

- [20 Points, 2-3 page]

  Data Processing and Summary Statistics:

  - Many variables in this dataset are in text format. For example, the `engine` variable may contain information such as horsepower, the number of cylinders, and fuel type. Process these variables to extract relevant information and create new variables for analysis.
  - Describe each data processing step, including your reasoning and any software packages used.
  - Some variables also contain missing values. Discuss how you handled these missing values and why you chose that approach.
  - After constructing your final dataset, provide a table of summary statistics (search online if you’re unfamiliar with this concept) for the key variables. You can also consider using frequency table, histogram plot, etc to summarize the variables efficiently.
  - If your approach of creating new variables was inspired from the literature, include proper citations.
  - You may revisit this step after the unsupervised and supervised learning phase to refine your data processing. If so, clearly explain the changes made and why they were necessary.

- [15 Points, 2-3 pages]

  Unsupervised Learning

  - Apply at least three clustering algorithms to the processed dataset.
  - Determine the appropriate number of clusters and discuss the interpretability of these clusters. Do they hold any meaningful distinctions?
  - Examine whether the clustering results are associated with your outcome variable.
  - Summarize insights from the clustering results. How could they be useful for your supervised learning steps?

- [30 Points, 3-4 pages]

  Prediction Models

  - Implement at least five different regression models to predict the price and tune their parameters appropriately.
  - You may use models beyond those covered in this course. However, at least four models should be ones introduced in class. If you incorporate a new model, provide a detailed description of it.
  - All linear models (e.g., OLS) and penalized linear models (Lasso, Ridge, Elastic Net) will be treated as the same model. KNN and Nadaraya-Watson kernel estimators are treated as the same model. If you use KNN or NW Kernel Estimators, you should discuss what distance metric is used, especially for the categorical variables.
  - Tune each model carefully, and clearly explain the tuning process for each. State your evaluation criteria and, if multiple criteria are used, discuss their advantages and disadvantages.
  - Provide sufficient information, including tables, figures, and explanations, to illustrate the model-fitting results. Which model appears to perform best?
  - Identify the variable(s) you constructed that seem to be most predictive, and provide interpretations of their impact on the model.

- [10 Points, 1 page]

   Open-Ended Question

  - A researcher is interested in estimating the original price of the cars in your dataset as if they were brand new. How would you approach this problem?
  - Since your dataset lacks information on new car prices, some form of extrapolation may be necessary (but feel free to explore alternative ideas). Discuss the challenges and limitations your approach may face.
  - Perform this prediction (use just one model is sufficient) by selecting three cars from your dataset and estimating their price as if they were new. Search online for the original release prices of these cars and compare these with your predictions. Discuss any discrepancies and potential reasons for these differences.

- [10 Points]

  General requirements

  - Is your report easy to read with clear logic?
  - For any model fitting with subjective decisions, provide reasoning for your decisions.
  - Is it written in a manner such that a reader does not need to be very familiar with the data?
  - Are plots, tables, etc. informative and correctly displayed and compact enough? For example, you should not include a super long table or a huge figure that takes a whole page.
  - Are irrelevant/trivial code/output hidden? Overall, **no more than 2 pages of the space** should be used as displaying the code.