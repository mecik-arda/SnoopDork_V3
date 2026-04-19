# SnoopDork_V3 - Dinamik Hedef Odaklı OSINT Dork Üretici / Dynamic Target-Oriented OSINT Dork Generator

Bu dosya hem Türkçe hem de İngilizce dokümantasyon içermektedir. / This file contains both Turkish and English documentation.

---

## Türkçe Dokümantasyon

SnoopDork_V3, siber güvenlik uzmanları, penetrasyon test uzmanları ve OSINT araştırmacıları için geliştirilmiş, dinamik ve hedef odaklı bir sorgu üreticisidir. İstemci tarafında çalışan tek bir HTML dosyası mimarisine sahip olan bu araç, herhangi bir sunucu veya harici bağımlılık gerektirmeden hedef alan adı üzerindeki bilgi toplama süreçlerini hızlandırmayı amaçlar.

**Önemli Not:** Bu projenin kaynak kodu (değişkenler, fonksiyonlar ve HTML yapısı) ve kullanıcı arayüzü tamamen Türkçe dilinde geliştirilmiştir.

### Öne Çıkan Özellikler

* Geniş Kapsamlı Dork Kategorileri: Açık dizinler, ifşa olmuş hassas dosyalar (.env, .config vb.), veritabanı yedekleri, yapılandırma dosyaları, sızdırılmış dokümanlar ve admin panelleri tespiti.
* Entegre Platform Sorguları: Google ve Shodan arama motorlarının yanı sıra GitHub ve Pastebin üzerinden kod ve sızıntı analizi.
* Altyapı ve Teknoloji Analizi: BuiltWith, StackShare, Wayback Machine, ViewDNS ve crt.sh (SSL Kayıtları) servislerine doğrudan entegrasyon.
* Güvenli Çalışma Modları:
    * Karanlık/Aydınlık Tema: Göz yormayan arayüz seçenekleri.
    * Gizlilik Modu (Stealth Mode): Toplu alanlarda çalışırken hedef verilerini ve dorkları blurlayarak gizleyen özel mod.
* Operasyonel Kolaylık:
    * Her dork için detaylı açıklama (Tooltip).
    * Tek tıkla kopyalama veya tüm sonuçları .txt olarak indirme.
    * Sıfır bağımlılık: Tek bir HTML dosyası ile her yerde çalışır.

### Kurulum ve Kullanım

SnoopDork_V3 herhangi bir kurulum veya bağımlılık gerektirmez.

1.  SnoopDork_V3.html dosyasını indirin.
2.  Dosyayı modern bir web tarayıcısı (Chrome, Firefox, Brave vb.) ile açın.
3.  Hedef alan adını (örneğin: hedef.com) girin.
4.  "Dork Üret" butonuna basarak analize başlayın.

### Yasal Uyarı

Bu araç, yalnızca eğitim, akademik araştırma ve yasal sınırlar çerçevesinde gerçekleştirilen yetkili penetrasyon testlerinde kullanılmak üzere geliştirilmiştir. Hedef sistemler üzerinde yetkisiz tarama veya bilgi toplama faaliyeti gerçekleştirmek yasa dışıdır. SnoopDork_V3'ün kullanımından ve elde edilen verilerin sonuçlarından doğabilecek her türlü hukuki sorumluluk tamamen son kullanıcıya aittir.

---

## English Documentation

SnoopDork_V3 is a dynamic and target-oriented query generator developed for cybersecurity professionals, penetration testers, and OSINT researchers. Featuring a client-side, single HTML file architecture, this tool aims to accelerate the reconnaissance process on a target domain without requiring any server or external dependencies.

**Important Note:** The source code of this project (including variables, functions, and HTML structure) and the user interface are developed entirely in the Turkish language.

### Key Features

* Comprehensive Dork Categories: Detection of open directories, exposed sensitive files (.env, .config, etc.), database backups, configuration files, leaked documents, and admin panels.
* Integrated Platform Queries: Code and leak analysis via GitHub and Pastebin, in addition to Google and Shodan search engines.
* Infrastructure and Technology Analysis: Direct integration with BuiltWith, StackShare, Wayback Machine, ViewDNS, and crt.sh (SSL Records) services.
* Secure Operation Modes:
    * Dark/Light Theme: Visual interface options for different environments.
    * Stealth Mode: A dedicated mode that blurs target data and dorks to maintain privacy in public spaces.
* Operational Convenience:
    * Detailed explanations for each dork via tooltips.
    * One-click copy functionality or batch download as a .txt file.
    * Zero dependencies: Operates as a standalone HTML file.

### Installation and Usage

SnoopDork_V3 does not require any installation or external libraries.

1.  Download the SnoopDork_V3.html file.
2.  Open the file using a modern web browser (Chrome, Firefox, Brave, etc.).
3.  Enter the target domain name (e.g., target.com).
4.  Click the "Dork Üret" (Generate Dork) button to begin the analysis.

### Legal Disclaimer

This tool is developed solely for educational purposes, academic research, and authorized penetration testing conducted within legal boundaries. Performing unauthorized scanning or information gathering activities on target systems is illegal. All legal responsibility arising from the use of SnoopDork_V3 and the resulting data belongs entirely to the end user.

---
**Geliştirici / Developer:** Arda Meçik
**Lisans / License:** MIT
