# 🧹 Marketing Campaign Dataset Cleaner

This repository contains a Python script to clean and preprocess a marketing campaign dataset using **pandas**. It includes column renaming, date formatting, age calculation, missing value handling, and dataset export.

# 📂 Dataset

The original dataset should be in **CSV format** with **tab-separated (`\t`) values**.

**File:**  
`marketing_campaign.csv`

# ⚙️ Features of the Cleaning Script

- Load dataset with tab (`\t`) delimiter  
- Standardize column names: lowercase, underscores, no special characters  
- Convert `dt_customer` to `DD-MM-YYYY` format  
- Calculate age from `year_birth`  
- Fill missing values in the `income` column with the mean  
- Remove duplicates  
- Trim whitespace in string columns  
- Save the cleaned dataset as `cleaned_dataset.csv`

# 🧪 Dependencies

Install the following Python library:

- pandas

# 🚀 Usage

1. Clone the repository  
2. Place `marketing_campaign.csv` in the working directory  
3. Run the script in any Python environment  

**Output:**  
`cleaned_dataset.csv`

# 🖼️ Code Snapshot

![Code Screenshot](images/code_snap%20(1).png)

# 📤 Output Preview

![Output Screenshot](images/code_snap%20(2).png)

# 📌 Notes

- Ensure the CSV file uses **tab (`\t`)** as the delimiter  
- The script fills missing values only in the **income** column. Expand as needed.
