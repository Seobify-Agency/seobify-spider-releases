# Seobify Spider

[Türkçe](#türkçe) · [English](#english)

## Türkçe

Seobify Spider, sitenizi bilgisayarınızda tarayıp teknik SEO sorunlarını bulan ücretsiz bir masaüstü uygulamasıdır. URL sınırı yoktur. Bu depo yalnızca Windows kurulum dosyalarını ve otomatik güncelleme bilgisini barındırır; kaynak kod paylaşılmaz.

**Neler yapar:**
- **Tarama:** HTTP/2 ile hızlı tarama, robots.txt ve site haritası desteği, duraklat ve sürdür, isteğe bağlı JavaScript işleme, giriş gerektiren siteler.
- **Denetim:** 200'den fazla SEO kuralı. Ayrıca yinelenen içerik, canonical ve hreflang denetimi, kırık bağlantılar, yönlendirme zincirleri, iç bağlantı gücü (PageRank), site sağlık skoru, erişilebilirlik (WCAG 2.1 AA) ve Türkçe okunabilirlik.
- **Yapay zeka görünürlüğü (GEO):** llms.txt kontrolü, yapay zeka botlarının erişim denetimi, alıntılanabilirlik skoru.
- **İçerik izi:** görünmez karakterler, yapıştırma kalıntıları, tekdüze yazım sinyalleri; isterseniz kendi yapay zeka anahtarınızla yeniden yazım.
- **Raporlar ve entegrasyonlar:** HTML, CSV ve XLSX raporları; Search Console ve GA4 birleştirmeleri; zamanlanmış tarama.
- **Claude ve diğer yapay zeka araçları:** yerleşik MCP sunucusuyla tarama, bulguları alma ve düzeltmeyi doğrulama.

**İndirme:** [Sürümler sayfasından](https://github.com/seobify/seobify-spider-releases/releases) en yeni `Seobify.Spider_<sürüm>_x64-setup.exe` dosyasını indirip çalıştırın (Windows 10/11, 64 bit). Python ya da başka bir şey kurmanız gerekmez. Kurulu uygulama yeni sürümleri kendisi bildirir.

Kurulum dosyası henüz kod imzalı değil. Windows "Windows bilgisayarınızı korudu" uyarısı gösterirse "Ek bilgi" → "Yine de çalıştır" deyin.

**Gizlilik:** Taramalar ve ayarlar bilgisayarınızda kalır; analitik ya da takip kodu yoktur. Uygulama yalnız şuralara bağlanır:
- taramanızı istediğiniz siteler,
- güncelleme kontrolü için bu depo,
- JavaScript işlemeyi ilk açtığınızda Chromium indirmesi,
- yalnız siz bağlarsanız Google Search Console, GA4, PageSpeed Insights ve seçtiğiniz yapay zeka sağlayıcısı (kendi anahtarınızla).

**Lisans:** Ücretsizdir; kişisel ve ticari kullanım serbesttir. Kullanım şartları: [TERMS.md](TERMS.md).

**Geri bildirim:** Hata ve önerileri [Issues](https://github.com/seobify/seobify-spider-releases/issues) bölümüne yazabilirsiniz; yanıt süresi taahhüdü yoktur.

Seobify'ın açık kaynak araçları (Log, Migrate, Optic): [Seobify Hub](https://github.com/Seobify-Agency/seobify-hub). Spider'ın bulgularını sitenizde uygulamak için [Seobify ile görüşün](https://seobify.com/iletisim/?utm_source=github&utm_medium=readme&utm_campaign=seobify-spider).

## English

Seobify Spider is a free desktop app that crawls your site on your own computer and finds technical SEO issues, with no URL limit. This repository only hosts the Windows installers and the auto-update file; the source code is not published.

**What it does:**
- **Crawling:** fast HTTP/2 crawling, robots.txt and sitemaps, pause and resume, optional JavaScript rendering, sites behind a login.
- **Audit:** 200+ SEO rules, plus duplicate content, canonical and hreflang audits, broken links, redirect chains, internal PageRank, a site health score, accessibility (WCAG 2.1 AA) and Turkish readability.
- **AI search visibility (GEO):** llms.txt checks, AI crawler access audit, citability score.
- **Content trace:** invisible characters, paste artifacts and uniform-writing signals, with an optional AI rewrite using your own API key.
- **Reports and integrations:** HTML, CSV and XLSX reports, Search Console and GA4 joins, scheduled crawls.
- **Claude and other AI tools:** a built-in MCP server lets an agent crawl, take the top issues and verify fixes.

**Download:** get the newest `Seobify.Spider_<version>_x64-setup.exe` from the [releases page](https://github.com/seobify/seobify-spider-releases/releases) and run it (Windows 10/11, 64-bit). Nothing else to install. The app tells you when a new version is out.

The installer is not code-signed yet. If Windows shows "Windows protected your PC", choose "More info" → "Run anyway".

**Privacy:** crawls and settings stay on your computer; there is no analytics or tracking. The app only connects to:
- the sites you ask it to crawl,
- this repository, to check for updates,
- the Chromium download the first time you turn on JavaScript rendering,
- Google Search Console, GA4, PageSpeed Insights and your chosen AI provider, only if you connect them (with your own key).

**License:** free for personal and commercial use. Terms: [TERMS.md](TERMS.md).

**Feedback:** report bugs and ideas in [Issues](https://github.com/seobify/seobify-spider-releases/issues); there is no response-time promise.

Seobify's open-source tools (Log, Migrate, Optic): [Seobify Hub](https://github.com/Seobify-Agency/seobify-hub). Need help applying what Spider finds? [Talk to Seobify](https://seobify.com/en/contact/?utm_source=github&utm_medium=readme&utm_campaign=seobify-spider).
