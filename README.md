# gurobi-tsp
Gurobi ile Gezgin Satıcı problemi (TSP With Gurobi)
# 📍 Gezgin Satıcı Problemi (TSP) – Gurobi & Python
Bu projede, **Gezgin Satıcı Problemi (Traveling Salesman Problem - TSP)** Python dili ve **Gurobi optimizasyon kütüphanesi** kullanılarak çözülmüştür. Amaç, belirli şehirler arasında en kısa rotayı bularak her şehrin yalnızca bir kez ziyaret edilip başlangıç noktasına dönülmesini sağlamaktır.

## 🔧 Kullanılan Teknolojiler

- Python 3.x  
- Gurobi Optimizer  
- Gurobi Python API  
- Microsoft Excel (Girdi ve çıktı dosyaları için)

## 📊 Problem Özeti

- Başlangıçta 10 şehir ile başlanmış, şehir sayısı adım adım artırılarak 20 şehre kadar çıkarılmıştır.
- Her örnek için şehirler arası mesafeler rastgele oluşturulmuştur.
- Girdi verileri ve çözüm sonuçları **Excel dosyaları** ile yönetilmiştir.

## 📁 Dosya İçeriği

- `dosya*.xlsx` – Çözülen rotaların ve toplam maliyetlerin bulunduğu çıktı dosyası.  

## ▶️ Nasıl Çalıştırılır?

1. Gurobi ve Python ortamınızı kurun.
2. Gurobi lisansınızı aktif hale getirin. (Akademik lisans için kampüs bağlantısı gereklidir.)
3. Excel ile gerekli eklentileri kurun (Problem Solver vb.) ve "solve Model" seçeneğini seçin.
4. Çözüm sonuçları otomatik olarak Excel formatında kaydedilir. "W" Sütununu kontrol ediniz sonuçlar için.

