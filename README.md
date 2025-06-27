🧼 Task-1: Data Cleaning Project using Jupyter Notebook
This repository contains a Jupyter Notebook focused on cleaning and preprocessing raw, unstructured data. The dataset initially contained missing values, duplicates, inconsistent formatting, and categorical noise, which were handled step-by-step using Python data tools.

📚 Libraries Used
pandas – Data manipulation and cleaning
numpy – Numerical operations
matplotlib – Basic plotting support
seaborn – Data visualization and analysis

🔧 Key Cleaning Steps Performed
📥 Data Loading and Initial Inspection
Loaded the dataset using read_csv() and displayed the output.
Saved a copy using to_excel() to review in Excel format.

🕳️ Handling Missing & Duplicate Data
Applied dropna() to remove rows with missing values and stored in new_drop.
Printed cleaned results using to_string().
Removed duplicate rows using drop_duplicates().

🔢 Column Cleaning & Formatting
Converted Age column to numeric using pd.to_numeric().
Filled missing values in Age with the mean age.
Applied unique() to the Gender column to view unique values.
Replaced missing/blank entries in the Email column with '-'.
Converted Join Date to datetime format using pd.to_datetime().
Converted Salary column to numeric for proper analysis.

🏢 Department Column Handling
Extracted unique values using unique().
Computed the mode and filled missing values in the Department column.

🚻 Gender Column Finalization
Replaced short values like M, F, NaN with full terms like Male, Female, Unknown for better readability.

✅ Final Output
A clean, well-structured dataset ready for visualization, machine learning, or analysis.

The notebook demonstrates step-by-step processing with code, comments, and output displays.

📂 File Structure
├── Task-1.ipynb         # Jupyter notebook with all cleaning steps
├── README.md            # Project documentation (this file)

🚀 How to Run
Clone the repository
Open Task-1.ipynb in Jupyter Notebook or Google Colab
Run all cells step-by-step

🏁 Status
✔️ Data cleaning complete
⚙️ Ready for further processing or model training
