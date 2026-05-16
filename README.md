# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-490-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 490                      |
| Total Reports: 15,893                |
| Unique Sources: 4,217                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4722 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2961 █████████████████████ ( 18.7%)
HTTP Admin Interface Probing ▏ 2054 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1540 ███████████ (  9.7%)
         HTTP Wordpress Scan ▏ 1396 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  854 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  661 ████ (  4.2%)
            HTTP CVE Probing ▏  574 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  449 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏  169 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  145 █ (  0.9%)
                 Netgear RCE ▏  127 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   59 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   50 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4988 ███████████████████████████████████ ( 38.3%)
United Kingdom ▏ 1779 ████████████ ( 13.6%)
       Ireland ▏ 1273 ████████ (  9.8%)
   Netherlands ▏  934 ██████ (  7.2%)
        France ▏  868 ██████ (  6.7%)
     Singapore ▏  740 █████ (  5.7%)
         Japan ▏  711 ████ (  5.5%)
        Canada ▏  669 ████ (  5.1%)
       Germany ▏  569 ███ (  4.4%)
     Australia ▏  507 ███ (  3.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-09 ▏   46 ███████████████████████ ( 12.6%)
2026-05-10 ▏   64 ████████████████████████████████ ( 17.5%)
2026-05-11 ▏   68 ███████████████████████████████████ ( 18.6%)
2026-05-12 ▏   50 █████████████████████████ ( 13.7%)
2026-05-13 ▏   47 ████████████████████████ ( 12.8%)
2026-05-14 ▏   59 ██████████████████████████████ ( 16.1%)
2026-05-15 ▏   29 ██████████████ (  7.9%)
2026-05-16 ▏    3 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!