🎓 ATÖxGem v7.0 (Absolut)
ATÖxGem is an advanced, Python-based academic assistant software designed to automate the tedious and time-consuming tasks of writing theses and academic papers in seconds.

It allows you to manage processes like cross-reference validation, smart PDF archive matching, and automatic source downloading from a single interface—automating the manual workflows where standard reference management tools (like Mendeley, EndNote) often fall short.

🚀 Key Features
1. Cross-Check & Error Analysis
Verifies whether the in-text citations (APA or Numbered system) actually exist in your bibliography list.

🟩 Green: Perfect match.

🟨 Yellow: "Suspicious" matches with minor typos or year discrepancies.

🟥 Red: Citations forgotten in the bibliography or "phantom references" not used in the text.

Reporting: Generates a detailed .txt error report and a color-coded Word document output.

2. PDF Archive Scanner (Archive Matching)
Reads the citations in your Word document, scans your local PDF archive (folder), and finds the matching articles.

Automatically copies all found PDFs into a new 1_Bulunan_PDFler folder.

Identifies and reports the missing articles that are not in your archive.

3. Bulk Download Panel (Link Harvester)
Scans your bibliography list to find the most up-to-date download links or DOI addresses on the internet (via CrossRef, Semantic Scholar, Europe PMC, Unpaywall).

HTML Panel: Presents the found links as an interactive HTML page.

One-Click Download: Allows you to simultaneously download all missing article PDFs via your browser using the "Open All" button.

4. Automatic APA 7 Bibliography Generator
Reads hidden metadata (like DOIs) inside matched PDFs, verifies them online, and lists these sources in a standard APA 7 formatted Word document (3_APA_Kaynakca.docx).

🛠️ Technical Infrastructure
Python 3.10+: Robust and flexible architecture.

Tkinter UI: Multi-language (TR, EN, ES, FR, DE), multithreaded (freeze-free) modern interface.

Python-Docx: Millimetric manipulation and color-coding on Word documents.

Regex Engine: Advanced text processing engine that parses citations and author names accurately.

API Integrations: Real-time data exchange with global open-access academic databases.

📂 File Structure and Outputs
When the program finishes its execution, it creates a folder based on your Word document's name containing:

1_Cift_Yonlu_Kontrol_Edilmis_Metin.docx: The color-coded main text where citations are verified.

1_Bulunan_PDFler/: The pool of matched articles collected for you from your archive.

2_Arsivde_Bulunamayan_Atiflar.txt: The list of missing sources.

3_APA_Kaynakca.docx: Automatically generated APA 7 bibliography.

5_Toplu_Indirme_Paneli.html: The interactive download interface for sources found on the internet.

🤝 Developer Note
ATÖxGem is designed with AI support (mostly Gemini 3.1 Pro) for researchers who want to use their time more efficiently while maintaining academic discipline. The software's goal is to reduce human error in formatting and control processes to zero, allowing the researcher to focus solely on the content.

--------------------------------------------------(TR)--------------------------------------------------

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
