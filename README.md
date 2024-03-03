# Home Mortgage Approval

## Contributors
* Ankit Mistry - GithubId: ankitm28
* Shivam Mistry - GithubId: smistry4

## Project Description
This is a Home Mortgage Approval prediction using three ML approaches namely MLP Classifier, Random Forest, and Ada Boost. We aim to find the most significant factors contributing to the approval or rejection of Home Mortgages. The dataset used in this project is sourced from [HMDA website](https://ffiec.cfpb.gov/data-browser/data/2022?category=states&items=TN&actions_taken=1,2,3) for the year 2022, specifically focused on the state of Tennessee. Furthermore, we have also conducted biasness analysis on the data.

## Requirements:
* Python, preferably 3.0 or greater

## Installation Instructions
1. Clone the HomeMortgageApproval repository.
2. After you have clone the repo, open the local folder and create a python environment using `create -m venv myenv`.
3. Activate the environment using `source myenv/bin/activate` in linux/MacOS, or using `source myenv/Scripts/activate` in a bash terminal in Windows.
4. Then install required libraries using `pip install numpy pandas matplotlib scikit-learn notebook`

## Usage
1. Download the dataset from the link provided in the description. Then create a folder named `Data`, and copy the dataset there. Do not change the name of the downloaded file.
2. Run the notebooks, recommended order: `fp_visuals`, `fp_mlpClf`, `fp_randomForest`, `fp_ada`.

## Future Work
* These ML models are trained on the data for the state of TN due to time and computational constraints. We would like to include national level dataset.
* A more thorough cleaning of the data.


