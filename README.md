# 🚢 Maritime Cyber Threat Intelligence (CTI) & OSINT Pipeline

Bu proje, denizcilik sektörüne ve jeopolitik krizlere yönelik açık kaynak istihbaratı (OSINT) toplamak ve saldırı yüzeyini haritalandırmak amacıyla bulut ortamında geliştirilmiş otomatize bir araçtır. 

Yönetim Bilişim Sistemleri (YBS) disipliniyle ele alınan bu çalışma; veri madenciliği, bulut teknolojileri ve siber güvenlik konseptlerini bir araya getirerek, tehdit istihbaratı (CTI) süreçlerinin keşif (reconnaissance) aşamasını simüle etmektedir.

## 🚀 Özellikler ve Analiz Aşamaları

### 1. Metin Madenciliği ile Gündem İstihbaratı
* Global haber kaynaklarından (RSS) otomatik veri çekilerek (Web Scraping) yapılandırılmamış metin verileri toplanmıştır.
* Elde edilen veriler üzerinde Python ile metin madenciliği uygulanarak oluşturulan Kelime Bulutu (Word Cloud) sayesinde krizin ana aktörleri tespit edilmiştir.

### 2. Saldırı Yüzeyi Haritalama (Attack Surface Mapping)
* Bölgedeki kritik liman otoritelerinin (ve OSINT araçlarının) domainleri üzerinden DNS Recon ve IP Geolocation teknikleri uygulanmıştır.
* `Banner Grabbing` yöntemiyle kurumların sunucu altyapıları (kullandıkları teknolojiler ve WAF/Cloudflare gibi güvenlik kalkanları) tespit edilmiştir.
* Elde edilen siber istihbarat verileri `Folium` kütüphanesi kullanılarak interaktif bir siber keşif haritasına (HTML) dökülmüştür.

## 🛠️ Kullanılan Teknolojiler
* **Programlama Dili:** Python
* **Kütüphaneler:** Pandas, BeautifulSoup, WordCloud, Folium, Requests, Socket
* **Geliştirme Ortamı:** Google Colab (Cloud-based)
* **Odak Alanları:** Cyber Threat Intelligence, Data Mining, Web Scraping, Network OSINT# Maritime-Cyber-Threat-Intelligence
Cloud-based OSINT and Attack Surface Mapping tool for maritime infrastructure.
