🧼 Task-1: Data Cleaning Project using Jupyter Notebook
This repository contains a Jupyter Notebook focused on cleaning and preprocessing raw, unstructured data. The dataset initially contained missing values, duplicates, inconsistent formatting, and categorical noise, which were handled step-by-step using Python data tools.

📚 Libraries Used
1) pandas – Data manipulation and cleaning
2) numpy – Numerical operations
3) matplotlib – Basic plotting support
4) seaborn – Data visualization and analysis
   
🔧 Key Cleaning Steps Performed

📥 Data Loading and Initial Inspection

1) Loaded the dataset using read_csv() and displayed the output.
2) Saved a copy using to_excel() to review in Excel format.

🕳️ Handling Missing & Duplicate Data
1) Applied dropna() to remove rows with missing values and stored in new_drop.
2) Printed cleaned results using to_string().
3) Removed duplicate rows using drop_duplicates().

🔢 Column Cleaning & Formatting

1) Converted Age column to numeric using pd.to_numeric().
2) Filled missing values in Age with the mean age.
3) Applied unique() to the Gender column to view unique values.
4) Replaced missing/blank entries in the Email column with '-'.
5) Converted Join Date to datetime format using pd.to_datetime().
6) Converted Salary column to numeric for proper analysis.

🏢 Department Column Handling

1) Extracted unique values using unique().
2) Computed the mode and filled missing values in the Department column.

🚻 Gender Column Finalization

Replaced short values like M, F, NaN with full terms like Male, Female, Unknown for better readability.

✅ Final Output

1) A clean, well-structured dataset ready for visualization, machine learning, or analysis.

2) The notebook demonstrates step-by-step processing with code, comments, and output displays.

📂 File Structure

├── Task-1.ipynb         # Jupyter notebook with all cleaning steps
├── README.md            # Project documentation (this file)

🚀 How to Run

1) Clone the repository
2) Open Task-1.ipynb in Jupyter Notebook or Google Colab
3) Run all cells step-by-step

🏁 Status

✔️ Data cleaning complete
⚙️ Ready for further processing or model training
