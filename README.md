# Araba Fiyat Tahmini Projesi

Bu proje, çeşitli özelliklere (yıl, model vb.) dayanarak kullanılmış araba fiyatlarını tahmin etmek için bir makine öğrenimi modeli oluşturmayı ve eğitmeyi amaçlamaktadır. Projede veri işleme ve model oluşturma için TensorFlow kütüphanesi kullanılmıştır.

## İçerik

Bu depo aşağıdaki Jupyter Notebook dosyasını içermektedir:

* **`tensorflowArabaDataframe.ipynb`**: Bu not defteri, araba fiyatları veri setinin yüklenmesi, keşfedilmesi, ön işlenmesi (eksik değerlerin ele alınması, kategorik değişkenlerin dönüştürülmesi vb.) ve ardından TensorFlow/Keras ile bir regresyon modelinin oluşturulması, eğitilmesi ve değerlendirilmesi adımlarını detaylı olarak göstermektedir. Modelin performansı genellikle Ortalama Kare Hata (Mean Squared Error - MSE) gibi metriklerle değerlendirilir. Ayrıca, eğitilmiş modelle yeni tahminler yapma süreci de ele alınmıştır.

## Özellikler

* Araba satış verilerinin Pandas DataFrame'i olarak yüklenmesi ve analizi.
* Veri seti üzerinde istatistiksel analiz ve görselleştirmeler.
* Model eğitimi için verilerin ölçeklendirilmesi (StandardScaler).
* TensorFlow ve Keras ile çok katmanlı bir yapay sinir ağı regresyon modeli oluşturma.
* Modelin eğitimi, kayıp (loss) ve metrik (metric) takibi.
* Eğitilmiş modelin performansı ve yeni veri noktaları için fiyat tahmini yapma.


## Kullanılan Teknolojiler

* **Python**
* **Pandas**: Veri yükleme, manipülasyonu ve analizi için.
* **NumPy**: Sayısal işlemler için.
* **TensorFlow / Keras**: Derin öğrenme modeli oluşturma ve eğitme için.
* **Scikit-learn**: Veri ön işleme (veri bölme, ölçeklendirme) için.
* **Matplotlib / Seaborn**: Veri görselleştirmeleri için.

## Katkıda Bulunma

Bu projeye katkıda bulunmaktan çekinmeyin. Her türlü geri bildirim, hata düzeltmesi veya yeni özellik önerisi kabul edilir. Lütfen bir "issue" açarak veya bir "pull request" göndererek katkıda bulunun.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakınız.
