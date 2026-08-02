📊 Global AI Job Market & Salary Trends — Tableau Analysis

Course: IST332 – Data Visualization Methods  
Instructor: Dr. Elif Kozan  
Term: 2024–2025 Spring  
Student: Buse Yurt · Ege University, Faculty of Science – Department of Statistics  

---

📁 Dataset
Global AI Job Market and Salary Trends 2025  
🔗 Kaggle Dataset  
Contains global AI industry data including job postings, salary figures, experience levels, employment types, and geographic location metrics.

---

🎯 Project Objective
This project utilizes Tableau to analyze global salary disparities, the relationship between experience and compensation, and country/industry-specific differences within the AI sector through 9 distinct data visualization techniques.

---

📌 Content & Performed Analyses

1. 🏷️ Data Labeling
Average salaries segmented by experience level (EN → EX) are displayed using a bar chart, with exact numerical labels added to each bar.  
Key Insight: Salary increases significantly with experience. Executive (EX) roles command the highest salaries, while Entry-level (EN) roles represent the lowest.

2. 🎨 Color Encoding
Job posting distributions by employment type (Full-time, Part-time, Contract, Freelance) are visualized using custom color coding.  
Key Insight: While Full-time positions dominate the market, the sector actively supports flexible and contract-based work models.

3. 🔍 Detail Shelf Usage
While displaying average salaries by job title, the `company_size` variable was added to the Detail shelf, allowing dynamic size-based comparisons via tooltips.  
Key Insight: Large enterprise companies offer distinctly higher compensation compared to small/medium companies for equivalent roles (e.g., Data Scientist).

4. 🔎 Data Filtering
An interactive country filter enables targeted single-country market analysis.  
Key Insight: Filtering specifically for Germany reveals exceptionally high compensation for Senior and Executive roles, whereas Entry-level baseline salaries remain relatively moderate.

5. 🧮 Calculated Fields
A custom metric titled `Salary Per Year of Experience` was engineered to evaluate efficiency across industries and geographic regions.  
Key Insight: Denmark and Norway yield noticeably high efficiency values across all sectors. This metric scales positively as seniority increases.

6. 📈 Time Series Analysis (Dual-Axis)
Total job posting counts (bars) and average salary figures (lines) by job title are integrated into a single visualization using a dual-axis layout.  
Key Insight: High-volume roles such as Data Scientist and Data Engineer do not top the salary rankings; niche positions like AI Architect yield higher compensation despite lower posting volumes.

7. 🗺️ Geographical Map Visualization
The geographic distribution of average salaries based on company location is mapped globally.  
Key Insight: The US, Switzerland, and Germany lead significantly in average compensation, while emerging markets reflect lower salary baselines.

8. ⚖️ Dual-Axis Supply & Demand Chart
Job posting density and salary levels are overlaid on a single axis pair to evaluate market supply-demand dynamics.  
Key Insight: High hiring volume does not strictly imply top-tier salaries; specialized, low-density roles command higher market premiums.

9. 🔵 Clustering & Trend Line Analysis
The relationship between years of experience and average salary is plotted on a scatter plot, segmenting data into 3 distinct clusters via Tableau's automatic clustering algorithm, complete with cluster-specific trend lines.

| Cluster | Profile |
| :--- | :--- |
| 🔵 **Cluster 1** | Low Experience – Low Salary (Entry-level roles) |
| 🟠 **Cluster 2** | Mid-Level Experience & Compensation |
| 🔴 **Cluster 3** | High Salary – Relatively Low Experience (Niche / Strategic roles) |

Key Insight: A positive correlation holds across all clusters; however, Cluster 3 demonstrates that high compensation is achievable with relatively low total experience in high-impact roles (e.g., AI Director, Principal Scientist).

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
Deneyim yılı ile ortalama maaş arasındaki ilişki scatter plot üzerinde gösterilmiş; Tableau'nun otomatik kümeleme algoritmasıyla 3 küme oluşturulmuştur.
 Her küme için ayrı trend çizgisi eklenmiştir.

KümeProfil
🔵 Cluster 1Düşük deneyim – Düşük maaş (giriş seviyesi roller)
🟠 Cluster 2Orta düzey deneyim ve maaş
🔴 Cluster 3Yüksek maaş – görece az deneyim (niş/stratejik roller)

Bulgu: Pozitif korelasyon tüm kümelerde geçerli, ancak kırmızı kümede az deneyimle bile yüksek maaş mümkün (AI Director, Principal Scientist gibi roller).
