# Sydney Airbnb Data Cleaning

A Python notebook for preparing Sydney Airbnb listings for an analysis of active short-stay rentals.

## What the project covers

- Checking missing values and exploring listing characteristics.
- Removing unnecessary columns and converting prices to numeric values.
- Filling missing bathroom and bedroom values.
- Extracting amenities and creating listing and host features.
- Filtering listings for the short-stay analysis and capping extreme prices.
- Validating and exporting the cleaned data.

## Run the notebook

1. Clone this repository and open its folder.
2. Install the dependencies:

   ```sh
   python -m pip install -r requirements.txt
   ```

3. Place the original Sydney Airbnb listings dataset in this folder as `listings.csv`. The data is not included in this repository. Use the dataset matching the notebook's expected columns.
4. Start Jupyter:

   ```sh
   jupyter lab 01_airbnb_cleaning.ipynb
   ```

5. Run the cells in order and review the output at each step.

The notebook writes `listings_clean.csv` to the project folder.

## Files

- `01_airbnb_cleaning.ipynb`: complete notebook, including its existing explanations and saved outputs.
- `requirements.txt`: packages needed to run the notebook.
- `.gitignore`: excludes local datasets, environments and notebook checkpoints.

## Notes

Recent reviews are used as an indicator of listing activity. The filtering and imputation rules are described in the notebook. Saved results reflect the original notebook run and may differ with another data snapshot. The notebook has been preserved as supplied; it was not rerun for this upload.
