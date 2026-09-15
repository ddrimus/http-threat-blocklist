# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-359-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--15-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 359                      |
| Total Reports: 20,144                |
| Unique Sources: 5,316                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6074 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3519 ████████████████████ ( 17.6%)
HTTP Admin Interface Probing ▏ 2488 ██████████████ ( 12.4%)
        HTTP Sensitive Files ▏ 2288 █████████████ ( 11.4%)
         HTTP Wordpress Scan ▏ 1526 ████████ (  7.6%)
      HTTP Crawl Non Statics ▏ 1105 ██████ (  5.5%)
            HTTP CVE Probing ▏  810 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.4%)
       CVE-2017-9841 Exploit ▏  589 ███ (  2.9%)
   CVE-2018-20062 (Thinkphp) ▏  249 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  238 █ (  1.2%)
                 Netgear RCE ▏  166 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   96 █ (  0.5%)
 HTTP Path Traversal Probing ▏   92 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6674 ███████████████████████████████████ ( 41.2%)
United Kingdom ▏ 1860 █████████ ( 11.5%)
   Netherlands ▏ 1491 ███████ (  9.2%)
       Ireland ▏ 1281 ██████ (  7.9%)
        France ▏ 1190 ██████ (  7.3%)
     Singapore ▏  858 ████ (  5.3%)
        Canada ▏  786 ████ (  4.9%)
         Japan ▏  764 ████ (  4.7%)
       Germany ▏  711 ███ (  4.4%)
      Bulgaria ▏  576 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-08 ▏   26 █████████████████ (  9.9%)
2026-09-09 ▏   39 ██████████████████████████ ( 14.8%)
2026-09-10 ▏   31 █████████████████████ ( 11.8%)
2026-09-11 ▏   33 ██████████████████████ ( 12.5%)
2026-09-12 ▏   51 ███████████████████████████████████ ( 19.4%)
2026-09-13 ▏   32 █████████████████████ ( 12.2%)
2026-09-14 ▏   46 ███████████████████████████████ ( 17.5%)
2026-09-15 ▏    5 ███ (  1.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!