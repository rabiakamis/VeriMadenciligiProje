## 📊 Veri Madenciliğine Giriş – Dönem Projesi  
### 🔍 Kullanılan Sınıflandırma Yöntemi: Random Forest

Bu proje, farklı makine öğrenmesi ve derin öğrenme algoritmalarını kullanarak *sınıflandırma problemlerini* çözmeyi amaçlamaktadır. KNN, Random Forest, Naive Bayes gibi klasik algoritmaların yanı sıra derin öğrenmeye dayalı modeller de karşılaştırmalı olarak uygulanmıştır.

---

## 📌 İçindekiler

- [📁 Proje Hakkında](#proje-hakkında)  
- [🧠 Kullanılan Algoritmalar](#kullanılan-algoritmalar)  
- [📚 Sınıflandırma Türleri](#sınıflandırma-türleri)  
- [⚙ Kurulum ve Kullanım](#kurulum-ve-kullanım)  
- [📈 Sonuçlar](#sonuçlar)  
- [🔗 Kaynaklar](#kaynaklar)  

---

## 📁 Proje Hakkında

Bu projede çeşitli makine öğrenmesi ve derin öğrenme algoritmaları kullanılarak veri sınıflandırma problemleri ele alınmıştır. Kullanılan algoritmaların doğruluk oranları ve genel başarıları farklı veri setleri üzerinde test edilerek karşılaştırılmıştır. Ayrıca, derin öğrenme modelleriyle farklı sınıflandırma türleri üzerinde analizler yapılmıştır.

Projede kullanılan veri seti, *gerçek dünya verilerini* içeren [bu makaleden](https://www.sciencedirect.com/science/article/pii/S2352340925001702) alınmıştır. Veri seti sınıflandırma algoritmalarının etkinliğini test etmek amacıyla kullanılmıştır.

---

## 🧠 Kullanılan Algoritmalar

### 🔹 K-Nearest Neighbors (KNN)
Veri noktalarının en yakın komşularına göre sınıf tahmini yapan, sezgisel ve etkili bir algoritmadır.

### 🔹 Random Forest
Birden fazla karar ağacından oluşan topluluk (ensemble) yöntemidir. Aşırı öğrenmeyi (overfitting) azaltarak daha dengeli sonuçlar verir.

### 🔹 Naive Bayes
Olasılıksal bir sınıflandırma algoritmasıdır. Özellikle metin sınıflandırma gibi doğal dil işleme uygulamalarında yaygın olarak tercih edilir.

### 🔹 Derin Öğrenme Modelleri
- Çok Katmanlı Algılayıcı (MLP)  
- Konvolüsyonel Sinir Ağı (CNN)  
- Tekrarlayan Sinir Ağı (RNN)  

Derin öğrenme yöntemleri, veriden otomatik olarak özellik çıkarımı yaparak özellikle karmaşık ve yüksek boyutlu veri kümelerinde üstün performans sergiler.

---
## Video linki : https://youtu.be/VXhfRFlG7J8
---

## ⚙ Kurulum ve Kullanım

Projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

```bash
git clone https://github.com/kullaniciadi/projeadi.git
cd projeadi
pip install -r requirements.txt
