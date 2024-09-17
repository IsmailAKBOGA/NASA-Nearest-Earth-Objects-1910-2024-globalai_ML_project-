
# NASA-Nearest-Earth-Objects-1910-2024-globalai_ML_project-
NASA | Nearest Earth Objects (1910-2024) data set Supervised and Unsupervised projects.
-


Gözetimli öğrenme (supervised) için neden Lojistik Regrasyon seçildi?
-

![supervised_result](https://github.com/user-attachments/assets/ec0485ce-225f-4db2-81a3-1fc9b2bab1af)

Bu veri kümesi, lojistik regresyon için uygundur çünkü "is_hazardous" sütunu ikili sınıflandırma (True/False) sunar. Sayısal özellikler olan "absolute_magnitude", "estimated_diameter_min", "relative_velocity" gibi veriler, tehlike durumunu tahmin etmek için kullanılabilir. Model, bu etiketli verilere dayanarak tahminler yapar.


Gözetimsi öğrenme (unsupervised) için neden Kmeans seçildi?
-

![unsupervised_result](https://github.com/user-attachments/assets/cdc4a748-8854-4147-bd56-5db4ee86cf2a)


KMeans, gözetimsiz öğrenme için kullanılan bir kümeleme algoritmasıdır ve etiketsiz verilerle çalışır. Bu veri kümesinde "is_hazardous" etiketi olmadan, asteroitler "absolute_magnitude", "estimated_diameter_min", "relative_velocity" gibi sürekli değişkenlerle doğal kümelere ayrılabilir. Asteroitler, büyüklükleri, hızları veya Dünya'ya yakınlıklarına göre gruplandırılabilir. KMeans, verideki gizli yapıları keşfederek farklı risk seviyelerinde gruplar oluşturulmasına olanak tanır.


Kaggle linkleri
-
Kaggle link:https://www.kaggle.com/work/collections/14592007 





