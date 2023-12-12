# Siber Güvenlik için Veri Madenciliği Projesi README

## Proje Hakkında

Bu proje, siber güvenlik alanında veri madenciliği tekniklerini kullanarak saldırıları tespit etmeyi amaçlamaktadır. Proje, Harran Üniversitesi Bilgisayar Mühendisliği bölümü öğrencileri Kerem SÖYLEMEZ ve Hasan GÜRSES tarafından gerçekleştirilmiştir.

## Kullanılan Teknikler

Bu proje kapsamında "Random Forest" algoritması tercih edilmiştir. Aşağıda, bu algoritmanın seçilme nedenleri ve kullanım avantajları belirtilmiştir:

1. **Yüksek Performans ve Hassasiyet:** Random Forest, sınıflandırma ve regresyon problemlerinde diğer algoritmaların önüne geçen bir performans sergiler. Toplu öğrenme yöntemi olarak, birden çok karar ağacını birleştirerek daha güçlü ve kararlı bir model elde edilir.

2. **Özellik Önem Sıralaması:** Random Forest, her ağacın oluşturulması sırasında rastgele seçilen özelliklerle eğitildiği için modelin özelliklerin önem sıralamasını sağlar. Bu, hangi özelliklerin modelin kararlarını daha fazla etkilediğini anlamamıza yardımcı olur.

3. **Aşırı Öğrenmeye Karşı Direnç:** Random Forest, rastgele özellik ve örnek seçimi gibi yöntemlerle aşırı öğrenmeye karşı dirençli hale getirilmiştir. Bu, modelin eğitim verilerine aşırı özelleşip genelleme yeteneğini kaybetme riskini azaltır.

4. **Geniş Veri Kümeleri ile Başa Çıkma Yeteneği:** Random Forest, genellikle büyük veri setleriyle etkili bir şekilde çalışabilir. Bu proje kapsamında, yüksek boyutlu veri kümelerini işlemek için kullanılmıştır.

5. **Gürültülü Veriye Karşı Dayanıklılık:** Gürültülü veri, veri madenciliği projelerinde yaygın bir sorundur. Random Forest, birden çok ağacın birleştirilmesi prensibi ile gürültülü veriye karşı daha dayanıklıdır.

## Proje Sonuçları

Proje sonuçları aşağıdaki başlıklar altında özetlenmiştir:

### DoS Saldırıları

- **Doğruluk (Accuracy):** 99.79%
- **Hassasiyet (Precision):** 99.89%
- **Geri Çağırma (Recall):** 99.69%
- **F-ölçü (F-measure):** 99.77%

### Probe Saldırıları

- **Doğruluk (Accuracy):** 99.65%
- **Hassasiyet (Precision):** 99.69%
- **Geri Çağırma (Recall):** 99.41%
- **F-ölçü (F-measure):** 99.51%

### U2R Saldırıları

- **Doğruluk (Accuracy):** 99.71%
- **Hassasiyet (Precision):** 97.24%
- **Geri Çağırma (Recall):** 85.93%
- **F-ölçü (F-measure):** 88.11%

### R2L Saldırıları

- **Doğruluk (Accuracy):** 97.99%
- **Hassasiyet (Precision):** 97.42%
- **Geri Çağırma (Recall):** 96.83%
- **F-ölçü (F-measure):** 97.31%
