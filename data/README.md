# Data – Euribor 3M

This folder contains the dataset used for calibrating the Vasicek model and running IRRBB stress tests.

## 📊 Dataset Description
- **Source**: [European Central Bank (ECB) / FRED](https://fred.stlouisfed.org/series/IR3TIB01FRM156N)  
- **Variable**: Euribor 3M (Euro Interbank Offered Rate, 3-month maturity)  
- **Frequency**: Daily observations  
- **Period**: ~10+ years of data  

## 📁 Files
- `IRR.csv` (or `.xlsx`) – cleaned dataset with two columns:  
  - `date` → timestamp of the observation  
  - `value` → 3M Euribor rate (expressed in decimal, not %)

⚠️ Note: The raw data is publicly available from ECB/FRED.  
Only a **processed/cleaned version** is stored here for reproducibility.  
