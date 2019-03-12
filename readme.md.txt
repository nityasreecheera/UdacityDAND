In this project a dataset containing the conversion rates between new and old websites for an e-commerce website is going to be analyzed.
The data will be used to perform an A/B test, the goal is to work through the notebook to help the community understand if they should implement the new page, keep the old one or run the experiment longer to make their decision.

Project Steps & Research Questions:
Data Wrangling:
->remove duplicates or records with missing or mismatched values
->handle the rows where the landing_page and group columns don't align

Data Analytics:
->Compute probabilities of converting:
->regardless of page.
->Given that an individual received the treatment
->Given that an individual received the control page
->Perform Hypothesis Testing and calculate p-values
->Conduct Logistic Regression