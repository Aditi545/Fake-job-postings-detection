# Fake-job-postings-detection
This project aims to classify job postings as real or fake using simple numerical features from job post text data.
We use features like:
1. title_length: Length of the job title
2. description_length: Length of the job description
3. has_company_profile: Whether the job has an associated company profile (1 for yes, 0 for no)
Using this data, we trained a Random Forest Classifier to detect fake postings.
We also visualized trends such as how fake jobs often have shorter titles or missing company profiles.
Accuracy: Overall percentage of correct predictions (e.g., 85%).

Classification Report:
1. Precision: Percentage of predicted fake jobs that are fake (e.g., 89%).
2. Recall: Percentage of actual fake jobs identified (e.g., 82%).
3. F1 Score: Balanced metric of precision and recall (e.g., 85%).
4. Confusion Matrix: Visualizes true positives, false positives, true negatives, and false negatives.
5. Prediction: Model predicts job posting as Fake or Real.
6. Visualization:
      Histogram shows title length distribution by job type.
      Bar plot shows prediction confidence.
      Confusion Matrix Heatmap: Visualizes prediction errors (e.g., false positives, false negatives).
