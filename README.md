# Transaction Clustering and Financial Analysis

This notebook focuses on clustering financial transactions, reducing dimensionality, and providing a visual analysis of categorized transaction data.

## Prerequisites

Make sure the following are installed before running the notebook:

- Python 3.11 or above
- Google collab / Jupyter Notebook
- Required Python packages listed in the notebook

### Install Dependencies

Install the common dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib openpyxl 
```

## Running the Notebook


1. **Open the notebook**:  
   Once Jupyter Notebook is running in your browser, open the file `transac 1(2).ipynb`.
   
   or
   
   **Open Google Collab**:
    Run the notebook in google collab.
3. **Add the Excel files**:  
   Make sure to place the required Excel files (containing transaction data) in the same directory as the notebook or update the file paths within the notebook if necessary.

6. **Run the notebook**:  
   Execute each cell sequentially to load data, perform clustering, and visualize the results.

## Notebook Overview

This notebook performs the following tasks:

- **Data Loading**: Loads transaction data from Excel files.
- **Data Processing**: Cleans and processes the transaction data.
- **Clustering**: Uses DBSCAN for clustering transactions based on categories such as `transferror name`, `transferror bank`, and transaction type.
- **Dimensionality Reduction**: Applies Principal Component Analysis (PCA) to reduce dimensions for better visualization.
- **Visualization**: Plots the clustered transactions to help with analysis.
- **Excel Export**: Saves the clustered data into a new Excel file for further use.

## Expected Output

After running the notebook, you can expect the following:

- A summary of transaction clusters.
- Visualization of clusters using PCA for dimensionality reduction.
- A new Excel file (e.g., `clustered_transactions.xlsx`) containing the categorized and clustered transaction data.

## Additional Notes

- Ensure that the Excel files are correctly formatted and contain the necessary columns (e.g., `date`, `cheque no`, `particulars`, `amount`, `transferror_type`, etc.).
- Adjust file paths and parameters in the notebook to fit your specific setup and data structure.
- For more detailed explanations, refer to the comments in each code cell of the notebook.

