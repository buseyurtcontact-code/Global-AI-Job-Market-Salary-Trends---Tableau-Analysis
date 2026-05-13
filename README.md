📊 Global AI Job Market & Salary Trends — Tableau Analysis

Course: IST332 – Veri Görselleştirme Yöntemleri
Instructor: Dr. Elif Kozan
Term: 2024–2025 Bahar
Student: Buse Yurt · Ege University, Faculty of Science – Statistics


📁 Dataset
Global AI Job Market and Salary Trends 2025
🔗 Kaggle Dataset
Global yapay zeka sektörüne ait iş ilanlarını, maaş bilgilerini, deneyim seviyelerini, çalışma biçimlerini ve ülke verilerini içermektedir.

🎯 Proje Amacı
Bu projede Tableau kullanılarak yapay zeka sektöründeki küresel maaş eşitsizlikleri, deneyim-maaş ilişkisi ve ülke/sektör bazlı farklılıklar 9 farklı görselleştirme tekniğiyle analiz edilmiştir.

📌 İçerik & Yapılan Analizler
1. 🏷️ Veri Etiketleme
Deneyim seviyelerine (EN → EX) göre ortalama maaşlar çubuk grafikle gösterilmiş; her çubuk üzerine sayısal etiket eklenmiştir.
Bulgu: Deneyim arttıkça maaş belirgin şekilde yükseliyor. Executive (EX) en yüksek, Entry-level (EN) en düşük maaşa sahip.

2. 🎨 Renklendirme
Çalışma biçimi türlerine (Full-time, Part-time, Contract, Freelance) göre iş ilanı dağılımı renk kodlamasıyla görselleştirilmiştir.
Bulgu: Tam zamanlı pozisyonlar çoğunlukta olsa da sektör, esnek ve proje bazlı çalışma modellerine de açık.

3. 🔍 Detail Kullanımı
İş unvanlarına göre ortalama maaşlar gösterilirken company_size değişkeni Detail olarak eklenmiş; tooltip üzerinden şirket büyüklüğü bazında karşılaştırma yapılabilmektedir.
Bulgu: Büyük ölçekli şirketler (örn. Data Scientist pozisyonunda) küçük şirketlere göre belirgin şekilde yüksek maaş sunuyor.

4. 🔎 Filtreleme
Ülke filtresiyle yalnızca seçilen ülkeye ait veriler analiz edilebilmektedir.
Bulgu: Almanya özelinde incelendiğinde Senior ve Executive pozisyonlarda maaşlar belirgin şekilde yüksek; Entry-level ise görece düşük.

5. 🧮 Hesaplanmış Alan
Yıllık Deneyim Başına Düşen Maaş adlı yeni bir metrik hesaplanarak sektör ve ülke bazında karşılaştırma yapılmıştır.
Bulgu: Danimarka ve Norveç tüm sektörlerde dikkat çekici yüksek değerler sunuyor. Deneyim arttıkça bu oran da yükseliyor.

6. 📈 Zaman Serisi (İkili Eksen)
İş unvanlarına göre ilan sayısı (bar) ve ortalama maaş (çizgi) ikili eksen kullanılarak tek görselde birleştirilmiştir.
Bulgu: Data Scientist ve Data Engineer gibi yoğun ilanlar maaş sıralamasında üst sıralarda değil; AI Architect gibi niş roller az ilanla yüksek maaş sunuyor.

7. 🗺️ Map (Harita)
Dünya genelinde şirket lokasyonuna göre ortalama maaşların coğrafi dağılımı haritada gösterilmiştir.
Bulgu: ABD, İsviçre ve Almanya açık ara öne çıkıyor. Gelişmekte olan ülkelerde maaşlar belirgin şekilde düşük.

8. ⚖️ İkili Eksen Grafiği
İlan yoğunluğu ile maaş seviyesi aynı grafik üzerinde birleştirilerek arz-talep dengesi incelenmiştir.
Bulgu: Yüksek ilan sayısı yüksek maaş anlamına gelmiyor; uzmanlık gerektiren az sayıdaki rol daha yüksek ücretlendiriliyor.

9. 🔵 Cluster & Trend Line
Deneyim yılı ile ortalama maaş arasındaki ilişki scatter plot üzerinde gösterilmiş; Tableau'nun otomatik kümeleme algoritmasıyla 3 küme oluşturulmuştur. Her küme için ayrı trend çizgisi eklenmiştir.
KümeProfil🔵 Cluster 1Düşük deneyim – Düşük maaş (giriş seviyesi roller)🟠 Cluster 2Orta düzey deneyim ve maaş🔴 Cluster 3Yüksek maaş – görece az deneyim (niş/stratejik roller)
Bulgu: Pozitif korelasyon tüm kümelerde geçerli, ancak kırmızı kümede az deneyimle bile yüksek maaş mümkün (AI Director, Principal Scientist gibi roller).
