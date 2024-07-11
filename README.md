
# Steel Fatigue Strenght Prediction using Machine Learning Model

Pemodelan ini memprediksi kekuatan lelah baja (*Steel Fatigue Strenght*) yang dipengaruhi oleh beberapa faktor seperti komposisi unsur kimia, suhu, dan kekerasan baja dengan menggunakan *machine learning*.


## Dataset

[data](https://github.com/alhadidmhmd/Steel_Fatigue_Prediction/blob/main/data.csv)
## Tools/IDE/Libraries

- Pyhton, bahasa pemrograman yang digunakan untuk pengembangan *machine learning model*.
- Visual Studio Code, *a versatile code editor* untuk pengembangan *machine learning model*.
- Seaborn, untuk visualisasi data statistik dan explorasi data dalam sains data dan analisis data.
- Numpy, untuk komputasi numerik yang efisien.
- Pandas, untuk manipulasi dan analisis data.
- Matplotlib, untuk visualisasi data.
- Scikit Learn, salah satu *open-source machine learning library* popular untuk bahasa pemrograman Python yang menyediakan *tools* sederhana dan efisien untuk *data mining* dan *data analysis*.
## Model

[Machine Learning Model](https://github.com/alhadidmhmd/Steel_Fatigue_Prediction/blob/main/Model.ipynb)
## Conclusion

Pengembangan dan penerapan model machine learning untuk memprediksi kekuatan lelah baja dapat meningkatkan efisiensi dan efektivitas dalam proses desain dan manufaktur di industri baja. Dengan mengetahui faktor-faktor apa saja yang mempengaruhi kekuatan lelah baja, kita dapat meningkatkan kualitas produk dengan mudah melalui penerapan machine learning.

Berdasarkan analisis yang dilakukan, model Random Forest terbukti sebagai model terbaik dengan nilai `R^2` tertinggi dan nilai MAE dan RMSE terendah. Selain itu, model Gradient Boosting dan Bagging juga sangat baik dan dapat dipertimbangkan sebagai alternatif.

Berdasarkan *correlation matrix*, beberapa fitur memengaruhi kekuatan lelah baja secara signifikan. Fitur-fitur seperti "TTt", "TT", "THT", "TTCr", "QmT", dan "Dt" memiliki korelasi yang kuat, baik positif maupun negatif, dengan "Fatigue". Korelasi positif menunjukkan bahwa peningkatan nilai fitur tersebut berkorelasi dengan peningkatan kekuatan lelah, sementara korelasi negatif menunjukkan bahwa peningkatan nilai fitur berkorelasi dengan penurunan kekuatan lelah.
