# Ai-Veri-Uretici

Bu proje, `Veri-Toplayici-Bot` tarafından toplanan gerçek insan kodlarını alır ve Gemini yapay zeka modelini kullanarak bu kodların "Yapay Zeka" stiliyle yeniden yazılmış versiyonlarını üretir. Amacı, kod tespiti modellerini eğitmek için sentetik veri sağlamaktır.

## ⚙️ Gereksinimler ve Kurulum

Bu projenin çalışabilmesi için hem bir API anahtarına hem de bir önceki projenin çıktısına ihtiyaç vardır.

* **Gemini API Token:** Yapay zeka ile metin/kod üretimi yapabilmek için geçerli bir Gemini API anahtarı gereklidir. Bu anahtarı proje ayarlarınıza eklemelisiniz.
* **Girdi Dosyası:** Bu yazılım sıfırdan veri üretmez. Çalışabilmesi için `Veri-Toplayici-Bot` tarafından oluşturulan kaynak kod veri setine ihtiyacı vardır.

## 🚀 Kullanım

1. Önkoşul olarak `Veri-Toplayici-Bot` projesini çalıştırıp kaynak veri setinizi oluşturun.
2. Oluşturduğunuz kaynak veri setini (`human_data.csv`) bu projenin ana dizinine veya belirtilen klasöre kopyalayın.
3. Gemini API anahtarınızı tanımlayın.
4. Programı çalıştırdığınızda, yapay zeka tarafından üretilen yeni kodlar `ai_data.csv` adıyla dışa aktarılacaktır.
