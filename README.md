# kaggle-notebooks-uspppm
Collection of notebooks for the [USPPPM Kaggle challenge](https://www.kaggle.com/competitions/us-patent-phrase-to-phrase-matching/)

- Data exctraction notebook ([USPPPM_data_extraction.ipynb](./USPPPM_data_extraction.ipynb)) for extracting additional samples from the training set by considering paths between 1-to-1 mappings (i.e. samples with score 1) and their direct neighbors and extracting data for the common chemical lookup-table as used in ([./uspppm-common-chemical-compound-lookup.ipynb](./uspppm-common-chemical-compound-lookup.ipynb))
- Chemical component lookup utity notebook ([./uspppm-common-chemical-compound-lookup.ipynb](./uspppm-common-chemical-compound-lookup.ipynb)) for augmenting the dataset with samples contructed from synonyms to common chemical formulae 
