
#  BTK DATATHON 2023
- This project focuses on prediction of customers segments according to given datasets. I made this project for DATATHON orginized by BTK Akademi.The project includes machine learning clustring,classification, exploratory data analysis (EDA), and data visualization techniques to gain insights into the dataset and understand its patterns. The project uses  train.csv,test_x.csv datasets, which can be downloaded from Kaggle: https://www.kaggle.com/competitions/datathon2023/data

- ![img](https://assets-btkakademi-gov-tr.akamaized.net/api/gallery/51/b7ffad66-04a1-4227-9db2-865a87ada5a6/datathon+2023_BANNER.png?t=1689860501481)



## DATA CONTENT
* train.csv - train set
* test_x.csv - test set
* sample_submission.csv - sample file upload format

### Feature description 

* İndex
* Cinsiyet
* Yaş Grubu
* Medeni Durum
* Eğitim Düzeyi
* İstihdam Durumu
* Yıllık Ortalama Gelir
* Yaşadığı Şehir
* En Çok İlgilendiği Ürün Grubu
* Yıllık Ortalama Satın Alım Miktarı
* Yıllık Ortalama Sipariş Verilen Ürün Adedi
* Eğitime Devam Etme Durumu
* Yıllık Ortalama Sepete Atılan Ürün Adedi
* Öbek İsmi - Tahmin edilecek olan etiket
## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scipy
- Sklearn

- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn 
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

* IMPORTING LIBRARIES

* LOADING DATASET

* DATA DESCRIPTION

* EXPLORATORY DATA ANALYSIS

* MISSING VALUES

* FEATURE ENGINEERING

* DATA VISUALIZATION

* OUTLIER DETECTION

* DATA PREPROCESSING

* CLUSTRING

* PREPARING DATA FOR CLASSIFICATION MODEL

* MODEL TRAINING AND EVALUATING

* MODEL TUNING

* SUBMISSION

* CONCLUSION


* The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 

* After exploratory analysis and visualization of the data sets, I used clustering algorithms to set the target tags based on the data, then added the tags I found to the data and made predictions using the classification algorithms with the final data. As a result of these predictions, I chose the model that gave the best result and adjusted its hyperparameters. Finally, I made predictions on the test dataset and saved these predictions as a csv file. I entered the contest by uploading this file via kaggle. I got the best accuracy result with the logistic regression model. The result I obtained with the logistic regression model was 98.62%.


