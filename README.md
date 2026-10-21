# Justice of the Peace Data
The Guardian spent 9 months investigating the Louisiana justice of the peace court system. In the process of our investigation, we created or acquired several datasets which we are releasing either in full or abridged form.

If you make use of this data, please cite the Guardian and [let me know](mailto:will.craft@theguardian.com).

## Datasets
#### [Court Fees](data/court_fees.csv)
This is a dataset of the total fees brought in per parish and the estimated salaries retained by the justices of the peace. Due to the possible errors in the financial statements from some courts, we aggregated to the parish level. 

|  Variable |  Definition |
|---|---|
|Parish| The parish of the justice or constable |
| Ward/District | The ward or district of the justice 
|Year | The year covering the financial statements
|Total fees | The sum of the court fees that the different courts within the parish brought in


#### [Evictions](data/evictions.csv)
This is an abridged dataset of the eviction documents gathered by the Guardian covering June 2025 to May 2026. We removed the plaintiff, defendant, and address columns. If you are a researcher or academic and feel that you need these columns, please reach out and the Guardian will evaluate a request to access the raw data. 

|  Variable |  Definition |  
|---|---|
id| The case ID
date_order | Date of the eviction case
waiver_or_first_notice | A flag indictating if the case involved a tenant waiving their right to notice. 
eviction_reason | The reason for the eviction as stated on the eviction order
defendant_represented | A flag indicating if there was any indication that the tenant had representation. This usually took the form of the word ATTY, SLLC, or ESQ next to the name of an individual written on the order next to the defendant. 
outcome | Outcome of the case. 

