# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-456-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--01--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 456                      |
| Total Reports: 10,665                |
| Unique Sources: 2,933                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3138 ███████████████████████████████████ ( 29.6%)
         HTTP Bad User Agent ▏ 2348 ██████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏ 1178 █████████████ ( 11.1%)
        HTTP Sensitive Files ▏ 1169 █████████████ ( 11.0%)
         HTTP Wordpress Scan ▏  688 ███████ (  6.5%)
      HTTP Crawl Non Statics ▏  445 ████ (  4.2%)
     HTTP Backdoors Attempts ▏  419 ████ (  3.9%)
       CVE-2017-9841 Exploit ▏  406 ████ (  3.8%)
            HTTP CVE Probing ▏  365 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  140 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  107 █ (  1.0%)
                 Netgear RCE ▏   87 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   47 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   40 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3315 ███████████████████████████████████ ( 36.2%)
United Kingdom ▏ 1668 █████████████████ ( 18.2%)
       Ireland ▏  999 ██████████ ( 10.9%)
   Netherlands ▏  696 ███████ (  7.6%)
        France ▏  507 █████ (  5.5%)
         Japan ▏  506 █████ (  5.5%)
     Singapore ▏  478 █████ (  5.2%)
       Germany ▏  357 ███ (  3.9%)
     Australia ▏  342 ███ (  3.7%)
         India ▏  288 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-05 ▏   29 ███████████████████ ( 10.4%)
2026-01-06 ▏   41 ███████████████████████████ ( 14.7%)
2026-01-07 ▏   29 ███████████████████ ( 10.4%)
2026-01-08 ▏   41 ███████████████████████████ ( 14.7%)
2026-01-09 ▏   52 ███████████████████████████████████ ( 18.7%)
2026-01-10 ▏   30 ████████████████████ ( 10.8%)
2026-01-11 ▏   47 ███████████████████████████████ ( 16.9%)
2026-01-12 ▏    9 ██████ (  3.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!