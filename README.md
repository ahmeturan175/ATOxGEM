🎓 ATÖxGem v7.0 (Absolut)

ATÖxGem, tez ve akademik makale yazım sürecinde araştırmacıların saatlerini alan "angarya" süreçleri saniyeler içinde otomatize eden, Python tabanlı gelişmiş bir akademik asistan yazılımıdır.

Standart referans yönetim araçlarının (Mendeley, EndNote vb.) eksik kaldığı çapraz atıf doğrulaması, akıllı PDF arşiv eşleştirmesi ve otomatik kaynak indirme gibi süreçleri tek bir arayüzden yönetmenizi sağlar.

🚀 Öne Çıkan Özellikler

1. Çapraz Kontrol (Cross-Check) & Hata Analizi

Metin içindeki atıfların (APA veya Numaralı sistem) kaynakça listesinde karşılığının olup olmadığını denetler.

🟩 Yeşil: Tam eşleşme.

🟨 Sarı: Yazım hatası veya yıl sapması olan "şüpheli" eşleşmeler.

🟥 Kırmızı: Kaynakçada unutulan atıflar veya metinde kullanılmayan "hayalet kaynaklar".

Raporlama: Detaylı bir .txt hata raporu ve renklendirilmiş bir Word çıktısı üretir.

2. PDF Arşiv Tarayıcı (Archive Matching)

Word belgenizdeki atıfları okur ve bilgisayarınızdaki PDF arşivinizi (klasörünüzü) tarayarak eşleşen makaleleri bulur.

Bulunan tüm PDF'leri otomatik olarak 1_Bulunan_PDFler klasörüne kopyalar.

Arşivinizde eksik olan makaleleri belirler ve raporlar.

3. Toplu İndirme Paneli (Link Harvester)

Kaynakça listenizi tarayarak her bir kaynağın internetteki (CrossRef, Semantic Scholar, Europe PMC, Unpaywall) en güncel indirme linkini veya DOI adresini bulur.

HTML Panel: Bulunan linkleri interaktif bir HTML sayfası olarak sunar.

Tek Tıkla İndirme: "Tümünü Aç" butonu ile eksik olan tüm makalelerin PDF'lerini tarayıcı üzerinden aynı anda indirmenize olanak tanır.

4. Otomatik APA 7 Kaynakça Oluşturucu

Eşleşen PDF'lerin içindeki gizli meta verileri (DOI vb.) okuyarak internetten doğrulama yapar ve bu kaynakları standart APA 7 formatında bir Word dosyası (3_APA_Kaynakca.docx) olarak listeler.

🛠️ Teknik Altyapı

Python 3.10+: Güçlü ve esnek mimari.

Tkinter UI: Çok dilli (TR, EN, ES, FR, DE), multithread (donma yapmayan) modern arayüz.

Python-Docx: Word belgeleri üzerinde milimetrik manipülasyon ve renklendirme.

Regex Engine: Atıfları ve yazar isimlerini parçalayan ileri düzey metin işleme motoru.

API Entegrasyonları: Global akademik veritabanlarıyla gerçek zamanlı veri alışverişi.


📂 Dosya Yapısı ve Çıktılar

Program çalıştığında ilgili Word belgesinin ismine göre bir klasör oluşturur:

1_Cift_Yonlu_Kontrol_Edilmis_Metin.docx: Atıfların doğrulandığı renklendirilmiş ana metin.

1_Bulunan_PDFler/: Arşivden sizin için toplanan makale havuzu.

2_Arsivde_Bulunamayan_Atiflar.txt: Eksik kaynakların listesi.

3_APA_Kaynakca.docx: Otomatik oluşturulmuş APA 7 kaynakçası.

5_Toplu_Indirme_Paneli.html: İnternette bulunan kaynaklar için indirme arayüzü.

🤝 Geliştirici Notu

ATÖxGem, akademik disiplini korurken zamanı daha verimli kullanmak isteyen araştırmacılar için yapay zeka desteği ile birlikte tasarlandı (çoğunlukla gemini 3.1 pro). Yazılımın amacı, format ve kontrol süreçlerindeki insan hatasını sıfıra indirerek araştırmacının sadece içeriğe odaklanmasını sağlamaktır.
