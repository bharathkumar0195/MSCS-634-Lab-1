# MSCS-634 Lab 1 — Data Visualization, Preprocessing and Statistics

**Student:** Bharath Kumar Origanti  
**University:** University of the Cumberlands

## Files
- `Lab_1_Data_Preprocessing_Analysis.ipynb`: executable Jupyter notebook with code, results and interpretation.
- `retail_sales_sample.csv`: synthetic sample data (80 records), generated for this assignment.
- `screenshots/`: chart images and selected result screenshots generated from the notebook.

## Run
1. Install Python 3.10+ and Jupyter Notebook.
2. Install packages: `pip install notebook pandas numpy matplotlib nbformat`
3. Keep the CSV beside the notebook.
4. Open the notebook using `jupyter notebook` and select **Run All Cells**.
5. Images are saved to the `screenshots` directory.

## Findings
The data has intentionally missing sales and marketing values and a high sales outlier. Median imputation handles missing entries; the IQR rule identifies extreme sales; outlier capping limits their impact. Charts show the distribution of sales and differences in mean sales across synthetic regions. The notebook reports central tendency, dispersion, and Pearson correlations.

## Decisions and limitations
The dataset is artificial, not a real company dataset. Imputation and capping affect the distribution. Random sampling reduces record count, and correlation is not causation.
