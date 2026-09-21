# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-376-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 376                      |
| Total Reports: 20,453                |
| Unique Sources: 5,386                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6161 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3543 ████████████████████ ( 17.5%)
HTTP Admin Interface Probing ▏ 2537 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2334 █████████████ ( 11.5%)
         HTTP Wordpress Scan ▏ 1529 ████████ (  7.5%)
      HTTP Crawl Non Statics ▏ 1126 ██████ (  5.5%)
            HTTP CVE Probing ▏  832 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.4%)
       CVE-2017-9841 Exploit ▏  613 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏  270 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  240 █ (  1.2%)
                 Netgear RCE ▏  169 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   96 █ (  0.5%)
 HTTP Path Traversal Probing ▏   94 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6746 ███████████████████████████████████ ( 41.3%)
United Kingdom ▏ 1862 █████████ ( 11.4%)
   Netherlands ▏ 1508 ███████ (  9.2%)
       Ireland ▏ 1282 ██████ (  7.9%)
        France ▏ 1195 ██████ (  7.3%)
     Singapore ▏  883 ████ (  5.4%)
        Canada ▏  787 ████ (  4.8%)
         Japan ▏  765 ███ (  4.7%)
       Germany ▏  717 ███ (  4.4%)
      Bulgaria ▏  582 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-14 ▏   44 ███████████████████████ ( 12.3%)
2026-09-15 ▏   65 ███████████████████████████████████ ( 18.2%)
2026-09-16 ▏   58 ███████████████████████████████ ( 16.2%)
2026-09-17 ▏   45 ████████████████████████ ( 12.6%)
2026-09-18 ▏   40 █████████████████████ ( 11.2%)
2026-09-19 ▏   59 ███████████████████████████████ ( 16.5%)
2026-09-20 ▏   46 ████████████████████████ ( 12.8%)
2026-09-21 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!