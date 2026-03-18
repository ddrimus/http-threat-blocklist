# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-368-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 368                      |
| Total Reports: 12,869                |
| Unique Sources: 3,414                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3798 ███████████████████████████████████ ( 29.7%)
         HTTP Bad User Agent ▏ 2615 ████████████████████████ ( 20.4%)
HTTP Admin Interface Probing ▏ 1556 ██████████████ ( 12.2%)
        HTTP Sensitive Files ▏ 1268 ███████████ (  9.9%)
         HTTP Wordpress Scan ▏ 1043 █████████ (  8.1%)
      HTTP Crawl Non Statics ▏  576 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  534 ████ (  4.2%)
            HTTP CVE Probing ▏  452 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  436 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  136 █ (  1.1%)
                 Netgear RCE ▏  104 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   53 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3930 ███████████████████████████████████ ( 36.4%)
United Kingdom ▏ 1754 ███████████████ ( 16.2%)
       Ireland ▏ 1142 ██████████ ( 10.6%)
   Netherlands ▏  800 ███████ (  7.4%)
     Singapore ▏  658 █████ (  6.1%)
         Japan ▏  651 █████ (  6.0%)
        France ▏  617 █████ (  5.7%)
       Germany ▏  468 ████ (  4.3%)
     Australia ▏  409 ███ (  3.8%)
         India ▏  371 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-11 ▏   16 ██████ (  5.7%)
2026-03-12 ▏   40 ███████████████ ( 14.1%)
2026-03-13 ▏   45 █████████████████ ( 15.9%)
2026-03-14 ▏   38 ███████████████ ( 13.4%)
2026-03-15 ▏   88 ███████████████████████████████████ ( 31.1%)
2026-03-16 ▏   27 ██████████ (  9.5%)
2026-03-17 ▏   22 ████████ (  7.8%)
2026-03-18 ▏    7 ██ (  2.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!