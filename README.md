
Bu proje, **orman yangını tespiti (Forest Fire Detection)** alanında farklı **makine öğrenmesi algoritmaları** ve **ön işleme (preprocessing)** tekniklerinin performanslarını karşılaştırmak amacıyla yürütülmüştür. Çalışmanın temel hedefi, aynı veri seti üzerinde çeşitli yöntemler uygulanarak hangi modelin yangın tespitinde daha yüksek doğruluk ve genelleme kabiliyeti sunduğunu belirlemektir.

Literatürde yapılan incelemeler, orman yangını tespitinde genellikle **görüntü işleme tabanlı yaklaşımlar**, **uzaktan algılama verileri** ve **sensör verilerinin analizi** gibi yöntemlerin yaygın olarak kullanıldığını göstermektedir. Ancak birçok çalışmada veri kalitesi, dengesiz sınıf dağılımı ve çevresel faktörlerin etkisi gibi unsurlar nedeniyle hatalı tespit oranlarının yüksek olduğu gözlemlenmiştir. Bu nedenle, bu projede veri ön işleme adımlarına özel önem verilmiş; gürültü giderme, normalizasyon, veri dengeleme ve özellik çıkarımı gibi işlemler farklı kombinasyonlarla test edilmiştir.

Deneysel süreçte, farklı algoritmaların (örneğin CNN tabanlı mimariler, SVM, Random Forest vb.) aynı veri seti üzerinde performans karşılaştırmaları yapılmıştır. Her bir algoritma için doğruluk, F1 skoru, precision ve recall gibi metrikler değerlendirilmiştir.

Projenin veri seti ve kaynak kodları, **etik ve akademik gereklilikler** doğrultusunda **açık olarak paylaşılmamaktadır.** Ancak gerçekleştirilen tüm deneyler, sonuçlar ve karşılaştırmalar, **tez çalışmasında detaylı biçimde açıklanmış ve görsel olarak sunulmuştur.**

Bu çalışma, hem literatürdeki mevcut yaklaşımları karşılaştırmalı olarak değerlendirmekte hem de orman yangını tespitinde kullanılabilecek alternatif yöntemlerin etkinliğini ortaya koymaktadır.

---------------------------------------------------------------------------------------------------------------------------------------------------------

This project focuses on **Forest Fire Detection**, aiming to compare the performance of various **machine learning algorithms** and **preprocessing techniques** on the same dataset. The main objective is to identify which model provides the highest accuracy and generalization capability for detecting forest fires under different experimental conditions.

A review of the literature shows that **image processing-based approaches**, **remote sensing data**, and **sensor data analysis** are commonly used in forest fire detection studies. However, many of these works suffer from high false detection rates due to issues such as data quality, class imbalance, and environmental variability. Therefore, this project places significant emphasis on the preprocessing stage, experimenting with different combinations of techniques such as noise reduction, normalization, data balancing, and feature extraction.

During the experimental phase, multiple algorithms (including CNN-based architectures, SVM, Random Forest, etc.) were tested on the same dataset, and their performances were evaluated using metrics such as accuracy, F1-score, precision, and recall.

For **ethical and academic reasons**, the **dataset and source code are not publicly shared**. However, all experiments, results, and performance comparisons are **clearly documented and visually presented in the thesis**.

This study contributes to the field by providing a **comparative evaluation of existing approaches** and demonstrating the **effectiveness of alternative methods** for improving forest fire detection systems.
