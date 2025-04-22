# Fake-job-postings-detection
This project aims to classify job postings as real or fake using simple numerical features from job post text data.
We use features like:
1. title_length: Length of the job title
2. description_length: Length of the job description
3. has_company_profile: Whether the job has an associated company profile (1 for yes, 0 for no)
Using this data, we trained a Random Forest Classifier to detect fake postings.
We also visualized trends such as how fake jobs often have shorter titles or missing company profiles.
