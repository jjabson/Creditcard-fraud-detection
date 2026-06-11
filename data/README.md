*Note:* Since the dataset is extremely large, this file will show how you access/get the dataset.

**Data Structure**
* **Shape:** 284,807 rows x 31 columns
* **Features:**
    * Time
    * Amount
    * V1-V28 (these V-features are typically PCA-transformed variables in this classic fraud dataset)
* **Target:** Class (0 = normal, 1 = fraud)
* **Missing values:** 0 across all columns (no imputation needed)

**Example:** How to use dataset:

```
from datasets import Dataset, concatenate_datasets, load_dataset

ds = load_dataset("David-Egea/Creditcard-fraud-detection")
```

Please go to Hugging Face website to see more info on the dataset.
