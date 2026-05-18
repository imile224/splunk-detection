# 🛡️ SOC Automation & Detection as Code (DaC) Portfolio

Bu layihədə Splunk SIEM mühiti üçün qaydaların (Detection Rules) mərkəzi idarə olunması və avtomatlaşdırılması təmin edilmişdir. 

## 🏗️ Arxitektura
Qaydalar GitHub Actions (CI/CD) vasitəsilə oxunur, validasiya edilir və REST API vasitəsilə dinamik olaraq Splunk-a push edilir. Tətiklənən alertlər anında Telegram kanalına yönləndirilir.

`GitHub (YAML) ➡️ GitHub Actions ➡️ Splunk REST API ➡️ Telegram Notification Bot`

## 🚀 Üstünlükləri
- **Mərkəzi İdarəetmə:** Bütün SIEM alertləri bir Git reposundan idarə olunur.
- **Dinamik Telegram Bildirişləri:** Hər bir qayda üçün kritiklik səviyyəsinə uyğun xüsusi bildiriş mətni təyin edilir.
