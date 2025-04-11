# NeutralABSA: Enhancing Neutral Sentiment Classification in Aspect Based Sentiment Analysis

This repository contains the **datasets** and **Jupyter notebooks** for **Aspect Extraction (AE)** and **Aspect Polarity Classification (APC)** as part of our research on improving **neutral sentiment classification** in **Aspect-Based Sentiment Analysis (ABSA)**.

## Brief Description
Aspect-Based Sentiment Analysis (ABSA) provides a detailed understanding of user opinions by identifying specific aspects within textual data and evaluating the sentiment associated with each. A key issue in this domain is the **misclassification of neutral cases**, where aspects are mentioned without a clear positive or negative sentiment.

This study focuses on improving the classification of **neutral sentiments** by addressing existing challenges such as **dataset imbalances**, **context overgeneralization**, and **unrelated aspect-sentence pairs**. The dataset used for this research includes the **SemEval 2014 - Laptop and Restaurant domains** as well as the **FABSA dataset**. Two main tasks are addressed: **aspect extraction** and **aspect polarity classification**.

To achieve the study's objectives, **BERT models** were fine-tuned using **LoRA-based Parameter-Efficient Fine-Tuning** to optimize aspect extraction and reduce context overgeneralization. Additionally, **data augmentation** was employed to address the issue of unrelated aspect-sentence pairs, improving the alignment between aspects and their corresponding sentiments. **Class-weighted DeBERTa training** was employed to mitigate dataset imbalances by assigning increased significance to neutral instances, thereby enhancing the model's capability to accurately classify neutral sentiments. The proposed approach demonstrated significant improvements in accurately identifying and classifying neutral sentiments.

## Usage Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/surabhiwaingankar/NeutralABSA.git
   cd NeutralABSA
   ```

2. **Explore the Notebooks**
   - Open the Jupyter notebooks provided in the repository to run aspect extraction and aspect polarity classification models.
   - Ensure you have Jupyter Notebook or JupyterLab installed to execute the notebooks.

3. **Datasets Used**
   - **Aspect Extraction (AE)**: SemEval 2014 datasets for Restaurants and Laptops.
   - **Aspect Polarity Classification (APC)**: SemEval 2014 datasets for Restaurants and Laptops, along with the FABSA dataset.

## Contributors
- [Surabhi Waingankar](https://github.com/surabhiwaingankar)  
- [Mahek Patel](https://github.com/patel-mahek)  

## License
This project is licensed under the MIT License. See the [LICENSE](https://mit-license.org/) file for more details.






