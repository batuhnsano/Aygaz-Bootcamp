# Aygaz-Bootcamp
Aygaz Makine Öğrenmesi bootcamp ilk projeyi içermektedir

**kaggle linli:** https://www.kaggle.com/code/batuhnsano/aygaz-mlproject-1-b



#**Gözeitmli Öğrenme**

Bu sonuçlar, dört farklı gözetimli öğrenme algoritması (Lojistik Regresyon, Naive Bayes, Karar Ağacı ve Rastgele Orman) kullanılarak yapılan model değerlendirmesinin özetini gösteriyor. Her bir model için Ortalama R-kare (R²) değeri ve Standart Sapma hesaplanmış. Şimdi bunları tek tek açıklayalım:

**1. Logistic Regression (Lojistik Regresyon)**
**Mean R²:** 0.6470
**Standard Deviation:** 0.0222
Lojistik regresyon modeli, bağımlı değişkeni tahmin etmede %64.7 oranında bir açıklama gücüne sahip. Yani, modelin tahmin ettiği sonuçlar ile gerçek sonuçlar arasındaki ilişkiyi fena olmayan bir doğrulukla yansıtmış.

Standart Sapma: 0.0222 ile oldukça düşük, yani modelin sonuçları farklı veri setlerinde tutarlı. R² değerleri arasında büyük bir oynama yok.

**2. Naive Bayes**
**Mean R²:** 0.5903
**Standard Deviation:** 0.0444
Naive Bayes modeli, bağımlı değişkeni %59.03 doğrulukla tahmin edebiliyor. Diğer modellere kıyasla en düşük R² değerine sahip, yani genel performansı daha zayıf.
Standart Sapma: 0.0444 ile lojistik regresyona göre biraz daha yüksek, bu da modelin farklı veri setlerinde daha fazla değişkenlik gösterdiğini, yani daha az tutarlı olduğunu gösterir.

**3. Decision Tree (Karar Ağacı)**
**Mean R²:** 0.7021
**Standard Deviation:** 0.0232
Karar ağacı, %70.21 doğrulukla bağımlı değişkeni açıklıyor. Lojistik regresyon ve Naive Bayes'ten daha iyi bir performans gösteriyor.
Standart Sapma: 0.0232, düşük bir oynama ile tutarlı bir model olduğunu gösterir.

**4. Random Forest (Rastgele Orman)**
**Mean R²:** 0.7107
**Standard Deviation:** 0.0194
Rastgele orman, en yüksek ortalama R² değeri ile %71.07 doğrulukta en iyi performansı gösteriyor. Bağımlı değişkeni açıklamakta en başarılı model bu.
Standart Sapma: 0.0194 ile en düşük sapmaya sahip, bu da modelin farklı veri setlerinde oldukça tutarlı sonuçlar verdiğini gösteriyor.

**Genel Değerlendirme:**

**En başarılı model:** Rastgele Orman (Random Forest), en yüksek ortalama R² ve en düşük standart sapmaya sahip olduğu için en başarılı model.
Karar Ağacı da iyi bir performans sergiliyor, ancak Rastgele Orman'a kıyasla biraz daha düşük.
Lojistik Regresyon, bu modeller arasında ortalama bir performans sergiliyor.
Naive Bayes, en düşük R² ve en yüksek standart sapmaya sahip olduğu için performans açısından en zayıf model.
Modeller arasındaki bu farklar, veri setinin yapısına ve modellerin bu verilere nasıl yaklaştığına göre değişebilir.
