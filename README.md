Məlumatların Oxunması və İlkin Baxış: Datasetin yüklənməsi, sütunların tiplərinin və statik göstəricilərinin təhlili (info(), describe()).

Məlumatların Təmizlənməsi (Data Cleaning & Imputation):

Age (Yaş) sütunundakı çatışmayan dəyərlərin median/ortalama ilə doldurulması.

Cabin sütununda həddən artıq boşluq olduğu üçün təmizlənməsi və ya kateqoriyalaşdırılması.

Embarked sütunundakı azsaylı çatışmayan dəyərlərin mod (ən çox təkrar olunan) ilə əvəzlənməsi.

Vizuallaşdırma və Qrafiklər (EDA):

Cinsiyyətə (Sex) və Bilet Sinfi dərəcəsinə (Pclass) görə sağ qalanların (Survived) faiz nisbəti.

Yaş paylanması və ailə tərkibinin (SibSp, Parch) sağ qalmaya təsiri.

Dəyişənlər arası korrelyasiya xəritəsi (heatmap).

🛠️ İstifadə Olunan Kitabxanalar
Pandas & NumPy (Data təmizləmə və analiz)

Matplotlib & Seaborn (Qrafiklər və vizuallaşdırma)


📂 Layihə Strukturu

├── data/               <- Titanic dataset faylı (train.csv / test.csv)
├── notebooks/          <- EDA və təmizləmə işlərinin aparıldığı Jupyter Notebook
└── README.md           <- Layihə təsviri
