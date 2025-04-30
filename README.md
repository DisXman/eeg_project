## **EEG Projesi – Aşamalar ve Yapılacaklar**

Bu belge, EEG projenin başarılı bir şekilde yürütülmesi için takip edilmesi gereken adımları ve her bir adımda yapılması gereken detaylı işlemleri açıklamaktadır.

---

### **ADIM 1 – README Dosyasını İncele ve Anlamaya Çalış**

**Amaç:** Projenin temel amacını ve kapsamını kavramak.

Aşağıdaki soruları net şekilde cevapla:

- Bu proje **hangi problemi çözmek** için tasarlanmış?
- Kullanılan **girdi verisi** nedir? (EEG sinyali, ancak dosya formatı ve örnek yapısı nasıl?)
- Projede kullanılan **etiket (label)** nedir? (Örnek: dikkat düzeyi, epileptik aktivite, zihinsel görev sınıflandırması vb.)
- Hangi **yöntem veya model** kullanılmış? (CNN, LSTM, klasik makine öğrenmesi yöntemleri?)
- Projenin **çıktısı** nedir ve nasıl yorumlanıyor?

---

### **ADIM 2 – Literatür Taraması Yap ve Raporla**

**Amaç:** Aynı probleme yönelik yapılmış önceki çalışmaları araştırarak karşılaştırma zemini oluşturmak.

- **Google Scholar**, **IEEE Xplore**, **PubMed**, **arXiv** gibi akademik kaynaklardan en az 5-6 benzer çalışma bul.
- Araştırma yaparken şu anahtar kelimeleri kullanabilirsin:
  - "EEG classification deep learning"
  - "EEG signal LSTM mental state"
  - "EEG emotion recognition using CNN"
- Her çalışmadan aşağıdaki bilgileri mutlaka not et:
  - Yazar(lar) ve yayın yılı
  - Kullanılan EEG veri kümesi (kaynağı, içeriği)
  - Kullanılan model mimarisi ve teknik yaklaşım
  - Başarı metrikleri (doğruluk, F1 skor, ROC-AUC vb.)
  - Eksik yönler, sınırlılıklar, geliştirilebilir alanlar

---

### **ADIM 3 – Proje Kodlarını Detaylı İncele**

**Amaç:** Projede kullanılan kodları satır satır analiz ederek işleyişi tam olarak anlamak.

- `eeg_project.ipynb` dosyasını aç ve incele.
- Verinin nasıl yüklendiğini, ön işlendiğini ve modele nasıl aktarıldığını tespit et.
- Model tipi nedir? (CNN, LSTM, MLP vb.)
- Eğitime ilişkin parametreleri belirle: epoch sayısı, batch size, optimizer, loss function vb.
- Performans ölçütleri nelerdir? (accuracy, confusion matrix, ROC-AUC gibi)

---

### **ADIM 4 – Yöntem (Methodology) Bölümünü Yaz**

Raporunun bu bölümünde aşağıdaki başlıklara detaylı şekilde yer ver:

1. **Veri Seti Bilgisi:**
   - Hangi kaynaktan elde edildi?
   - Kaç örnek içeriyor?
   - Sınıflar dengeli mi?
2. **Veri Ön İşleme Yöntemleri:**
   - Sinyal normalize edildi mi?
   - Zaman/pencereleme yapıldı mı?
   - Dönüşüm teknikleri (FFT, filtrasyon vb.) kullanıldı mı?
3. **Model Mimarisi:**
   - Kaç katman içeriyor?
   - Aktivasyon fonksiyonları neler?
   - Dropout, batch normalization gibi teknikler var mı?
4. **Eğitim Süreci:**
   - Kaç epoch?
   - Hangi optimizer kullanıldı?
   - Eğitim ortamı nedir? (Colab, GPU vb.)
5. **Değerlendirme Metrikleri:**
   - Hangi başarı kriterleriyle test edildi?

---

### **ADIM 5 – Sonuçları Görselleştir ve Yorumla**

**Amaç:** Modelin başarısını görselleştirerek güçlü ve zayıf yönlerini analiz etmek.

- Eğitim ve doğrulama sürecine ait accuracy ve loss grafiklerini çiz.
- Confusion matrix ile hangi sınıflarda hata yaptığını belirle.
- ROC eğrisini kullanarak modelin genel ayrıştırma gücünü analiz et.
- Özellikle “hangi sınıflar karışıyor?” sorusuna odaklanan açıklayıcı yorumlar yaz.

---

### **ADIM 6 – Literatürle Kıyaslama Yap**

**Amaç:** Proje sonucunun literatürdeki çalışmalarla karşılaştırılması.

- Elde ettiğin başarı oranı, literatürdeki çalışmalarla karşılaştırıldığında ne durumda?
- Modelin veya yaklaşımın farklı ya da yenilikçi yönleri var mı?
- Açıklanabilirlik açısından bir avantaj sağlıyor musun?
- Daha az veriyle benzer ya da daha iyi performans elde ettin mi?

---


