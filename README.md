# MusicGenreClassification

**Music Genre Classification Using Machine Learning**  
**December 2024**  

Developed an innovative machine learning approach for music genre classification, leveraging audio features rather than traditional metadata. This project addresses challenges in music information retrieval (MIR) by creating a novel dataset of nuanced "metal-like" genres compared to the standard GTZAN dataset.

- **Objective**: Improve accuracy and interpretability in classifying closely related music genres through handcrafted audio features and machine learning algorithms.  
- **Key Contributions**:  
  - Curated a dataset of 1,000 audio clips across 10 genres using YouTube, with 30-second segments focused on genre-defining characteristics.  
  - Extracted time-domain and frequency-domain features, such as Mel-frequency cepstral coefficients (MFCCs), spectral centroid, and chroma features, using Python's Librosa library.  
  - Implemented supervised models (Logistic Regression, SVM, Random Forest, XGBoost) and clustering techniques (t-SNE, GMM) to evaluate classification performance.  
  - Compared results to industry-standard GTZAN dataset, highlighting challenges in nuanced genre classification.  

- **Results**:  
  - Achieved 51.6% accuracy using SVM on the novel dataset, indicating significant challenges in distinguishing similar genres.  
  - Demonstrated near-perfect accuracy (99.9%) on GTZAN using XGBoost, validating the potential of machine learning for broader genres.  

- **Impact**: This work underscores the importance of robust feature extraction in MIR, with potential applications in music recommendation systems to enhance user engagement and satisfaction.  

**Skills Demonstrated**: Python, machine learning (Logistic Regression, SVM, Random Forest, XGBoost), data preprocessing, feature engineering, data visualization, and cross-validation.

**Future Direction**: Exploring deep learning models for improved performance on nuanced genres, advanced feature extraction methods, and integration with music streaming platforms.

GTZANdataset.ipynb contains the code for extracting and processing the data for the GTZAN dataset in the gtzan_features.csv
audioextraction.ipynb contains the code for extracting and processing the data for the custom music genre dataset in the df_features.csv
ModelCode.ipynb contains the code for running the models on the datasets
