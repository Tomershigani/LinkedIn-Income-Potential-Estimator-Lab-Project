# LinkedIn-Income-Potential-Estimator-Lab-Project

## Introduction
Welcome to the LinkedIn Income Potential Estimator: a cutting-edge tool developed by Data Scientists to empower LinkedIn users with personalized income insights. By analyzing salary data across various positions and incorporating advanced machine learning techniques, this tool aims to provide users with accurate estimations of their earning potential, matched to their unique skill sets and experiences.

## Features
- **Data Integration:** Merges comprehensive salary information from multiple sources, including Glassdoor and Indeed, to provide a balanced insight into the salary landscape.
- **Advanced Algorithms:** Utilizes state-of-the-art embedding techniques and clustering algorithms to tailor predictions and job listings.
- **User-Centric Design:** Empowers users with actionable knowledge to help identify and achieve their income goals.

## How It Works
1. **Data Collection:** Aggregates and enriches data from LinkedIn, Glassdoor, and Indeed to create a rich feature set.
2. **Algorithmic Processing:** Implements GloVe for text-data vectorization and k-means clustering to predict salary ranges.
3. **User Profile Analysis:** Crafts detailed user personas for testing and refinement of the predictive model.
4. **Job Matching:** Assigns user profiles to clusters and provides the top three job listings aligned with their profile.

## Usage
To get started with the LinkedIn Income Potential Estimator:
1. Clone this repository.
2. Install required dependencies listed in `requirements.txt`.
3. Run the main script with `python estimator.py` (Ensure you have your LinkedIn data available in the specified format).
4. Follow the on-screen prompts to input your professional details.

## Evaluation
Our model's effectiveness is evaluated using Silhouette Score and Within-Cluster Sum of Squares (WCSS) methods, with results visualized for optimal k-selection.

## Acknowledgments
- Special thanks to all the contributors who have invested their time in developing this tool.
- Gratitude to the data providers for making their resources available for analysis.

