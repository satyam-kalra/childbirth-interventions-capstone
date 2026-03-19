# Data Instructions

This project uses the following dataset:

> CIHI DAD/HMDB Childbirth 2024–2025 Data Tables (English)  
> URL: https://www.cihi.ca/sites/default/files/document/dad-hmdb-childbirth-2024-2025-data-tables-en.xlsx

Because of potential usage and redistribution restrictions, the raw Excel file is **not committed** to this repository.

## How to obtain the data

1. Visit the CIHI website and download the Excel file from:  
   `https://www.cihi.ca/sites/default/files/document/dad-hmdb-childbirth-2024-2025-data-tables-en.xlsx`

2. Save it into this folder with the following name:

```text
dad-hmdb-childbirth-2024-2025-data-tables-en.xlsx

3. The analysis notebooks reference this relative path:

```python
import pandas as pd

excel_path = "data/dad-hmdb-childbirth-2024-2025-data-tables-en.xlsx"
x = pd.ExcelFile(excel_path)
