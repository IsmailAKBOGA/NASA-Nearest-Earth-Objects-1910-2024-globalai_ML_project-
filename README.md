# NASA-Nearest-Earth-Objects-1910-2024-globalai_ML_project-
NASA | Nearest Earth Objects (1910-2024) data set Supervised and Unsupervised projects.
Kaggle link:https://www.kaggle.com/work/collections/14592007

Gözetimli öğrenme (supervised) için neden Lojistik Regrasyon seçildi?

Bu veri, gözetimli öğrenme için lojistik regresyona uygun çünkü ikili Sınıflandırma "is_hazardous" sütunu, bir nesnenin tehlikeli olup olmadığını gösteriyor (True/False). Bu, lojistik regresyonun temel işlevine uygun, yani bir olayın iki olasılıklı sonucunu (0 veya 1) olarak tahmin etmekte. Bağımsız Değişkenler: "absolute_magnitude", "estimated_diameter_min", "estimated_diameter_max", "relative_velocity", "miss_distance" gibi sayısal özellikler sınıflandırmayı etkileyebilecek önemli bilgiler sağlıyor. Lojistik regresyon bu özelliklerden yola çıkarak bir nesnenin tehlikeli olup olmadığını öğrenebilir.  Veri kümesinde her nesne için "is_hazardous" etiketi mevcut. Gözetimli öğrenmede, model bu etiketli verilere dayanarak öğrenme yapar ve yeni örnekler üzerinde tahminler yürütür. Bu nedenle, lojistik regresyon bu veri kümesinde "is_hazardous" (tehlikeli olup olmama) değişkenini tahmin etmek için uygun bir modeldir.


Gözetimsi öğrenme (unsupervised) için neden Kmeans seçildi?

KMeans algoritması, gözetimsiz öğrenme için kullanılan bir kümeleme algoritmasıdır. Gözetimsiz öğrenme modelinde, veri noktalarının gruplarını veya desenlerini keşfetmeye çalışır.

 Etiket Gerekmemesi:
  KMeans, etiketsiz verilerle çalışır ve bu veri kümesinde "is_hazardous" etiketini kullanmadan veri noktalarını doğal gruplarına ayırmak için kullanılabilir. KMeans, verilere dayalı olarak benzer özelliklere sahip olan asteroidleri kümeleyebilir.

 Sürekli Değişkenler:
  Bu veri setinde sayısal özellikler ("absolute_magnitude", "estimated_diameter_min", "estimated_diameter_max", "relative_velocity", "miss_distance") KMeans için uygundur. KMeans, bu sürekli değişkenleri kullanarak asteroidleri benzer özelliklere sahip olan kümelere ayırabilir. Örneğin, asteroidlerin büyüklükleri, hızları veya Dünya'ya yakınlıklarına göre gruplar oluşturulabilir.

 Asteroitlerin Farklı Gruplarını Bulma:
   KMeans, asteroitleri birbirine yakın özelliklere sahip gruplara (kümelere) ayırabilir. Örneğin, daha büyük ve Dünya'ya daha yakın olan asteroitlerle, küçük ve daha uzak asteroitler arasında kümeler oluşturabilir. "is_hazardous" bilgisi kullanılmadan, özelliklerine göre farklı risk seviyelerinde gruplar tanımlanabilir.

 İnsan Denetimi Olmadan Keşif:
  Veride gizli yapıları ortaya çıkarmak için uygundur. Örneğin, asteroitlerin tehlike seviyesine dair herhangi bir etiketi kullanmadan, belirli gruplar ve desenler keşfedilebilir. Bu da, araştırmacıların belirli özelliklere sahip olan asteroit gruplarını daha iyi anlamasına yardımcı olabilir.

![supervised_result](https://github.com/user-attachments/assets/ec0485ce-225f-4db2-81a3-1fc9b2bab1af)
![unsupervised_result](https://github.com/user-attachments/assets/cdc4a748-8854-4147-bd56-5db4ee86cf2a)
