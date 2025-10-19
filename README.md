# CSE400 Thesis
Topic: **Aspect Based Opinion Mining on Restaurant Reviews**


## 📖 Overview
This research project focuses on developing a **machine learning system for Aspect-Based Opinion Mining (ABOM)** to analyze restaurant reviews. With the rapid growth of online platforms, customers frequently share their opinions on food, service, ambiance, and pricing. However, the sheer volume of reviews makes manual analysis inefficient.  
Our study aims to automatically extract key aspects from customer feedback and classify their sentiments as **positive, negative, or neutral**, enabling data-driven decision-making for businesses and customers alike.


## 🎯 Objectives
- To perform **aspect extraction** from restaurant reviews.  
- To classify sentiment polarity for each aspect using **machine learning and deep learning models**.  
- To evaluate and compare the performance of different algorithms on benchmark datasets.  
- To provide an interpretable, scalable solution for real-world opinion mining.


## 🧠 Methodology
1. **Data Collection:**  
   Collected restaurant review data from publicly available datasets (e.g., TripAdvisor/Kaggle).

2. **Data Preprocessing:**  
   - Text cleaning (removal of noise, special characters, and stopwords)  
   - Lemmatization and tokenization  
   - Normalization and emoji/text processing  

3. **Aspect Extraction:**  
   - Implemented topic modeling with **Latent Dirichlet Allocation (LDA)** to identify major aspects such as *Food, Service, Ambiance,* and *Price*.

4. **Sentiment Classification:**  
   - Applied both **Traditional ML Models** (Naive Bayes, Random Forest, SVM)  
   - And **Deep Learning Models** (LSTM, BiLSTM)  
   - Used **GloVe Embeddings** for word vector representation.  
   - Employed **NLPaug** for data augmentation to improve class balance.

5. **Evaluation Metrics:**  
   Accuracy, Precision, Recall, and F1-score were used to compare model performance.


## 🧰 Technologies Used
- **Programming Language:** Python  
- **Libraries & Frameworks:** Pandas, NumPy, Scikit-learn, TensorFlow, Keras, NLTK, NLPaug, Matplotlib, Seaborn  
- **Algorithms:** Naive Bayes, Random Forest, SVM, LSTM, BiLSTM  
- **Embedding:** GloVe  
- **Topic Modeling:** LDA  


## 📊 Results
- Identified four key aspects: **Food, Service, Place, and Price**.  
- Deep learning models, particularly **BiLSTM**, achieved superior accuracy and F1-score compared to traditional ML models.  
- The model demonstrated strong capability in extracting context-aware sentiment patterns from unstructured text.


## 🏆 Key Achievements
- Built a complete NLP pipeline from raw text to aspect-level sentiment output.  
- Enhanced model performance through data augmentation and embedding optimization.  
- Provided valuable insights into customer behavior for the restaurant industry.  
- Contributed toward advancing automated opinion mining in domain-specific contexts.


## 📚 Citation
If you use this work or find it useful in your research, please cite it as:

> S. H. Tonmoy, F. B. Ahmed, M. Sarkar, M. B. Bashar, and R. Ahmed, *Aspect-Based Opinion Mining on Restaurant Reviews*, B.Sc. Thesis, Department of Computer Science and Engineering, BRAC University, 2024.


## 🤝 Contributors
- **Sazid Hasan Tonmoy** — Lead Researcher & Developer  
- **Faiyaj Bin Ahmed** — Data Processing & Model Development  
- **Madhurjya Sarkar** — NLP Pipeline & Evaluation  
- **Mehejabin Binta Bashar** — Literature Review & Documentation  
- **Rafi Ahmed** — Data Collection & Visualization  

**Supervisor:**  
- **Dr. Farig Yousuf Sadeque**  
  *Associate Professor, Department of Computer Science and Engineering*  
  📧 farig.sadeque@bracu.ac.bd  

**Co-Supervisor:**  
- **Mr. Moin Mostakim**  
  *Senior Lecturer, Department of Computer Science and Engineering*  
  📧 mostakim@bracu.ac.bd
 


## 📬 Contact
For queries or collaboration:  
📧 **sazid.hasan.tonmoy@g.bracu.ac.bd**


## 🧾 License
This project is for academic and research purposes only. Please contact the author for permission before reuse or publication.
