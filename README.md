# Malicious_URL
Our primary objective is to design an effective system for detecting malicious URLs, thereby reducing potential risks for online users. To achieve this goal, we chose to use a Support Vector Machine (SVM) model due to its capability to efficiently handle complex datasets and generalize learned models.

To address these issues, we worked on a system that detects malicious URLs using machine learning techniques. The critical aspect of malicious URL detection lies in feature extraction. We collected a training dataset, which was then trained on the extracted features. The main attributes we extracted are host-based, lexical-based, and popularity-based.

We selected the SVM model because of its ability to effectively process multidimensional data and linearly separate classes in the feature space. This model also provides flexibility for exploring different kernels, allowing us to experiment with various kernels to achieve the best classification results.

We will use this SVM model to build our malicious URL detection system and evaluate its performance on test and validation datasets. By carefully extracting URL features and using a well-tuned SVM model, we aim to provide an effective solution to protect users against online threats.
**Dataset Description:**
We utilized a comprehensive dataset of 651,191 URLs sourced from Kaggle, which includes:

428,103 benign or safe URLs
96,457 defacement URLs
94,111 phishing URLs
32,520 malware URLs
Data Sources
The dataset was constructed from the following components:

1- Benign, Phishing, Malware, and Defacement URLs:

The ISCX-URL-2016 dataset was used as the primary source for these URL types.

2- Augmentation of Phishing and Malware URLs:

We enhanced our dataset using a blacklist of malicious domains.

3- Augmentation of Benign URLs:

We referenced Faizan's Git repository to increase the count of benign URLs.

4- Phishing URLs Increase:

The Phishtank and PhishStorm datasets were also used to further augment our collection of phishing URLs.
**Data Collection Process**
The dataset comprises URLs collected from various sources. We found the Kaggle dataset pre-compiled and merged it into a cohesive format, retaining only the URLs and their respective class types.
