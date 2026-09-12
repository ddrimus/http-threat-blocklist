# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-343-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 343                      |
| Total Reports: 20,013                |
| Unique Sources: 5,279                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6034 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3508 ████████████████████ ( 17.7%)
HTTP Admin Interface Probing ▏ 2474 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2264 █████████████ ( 11.4%)
         HTTP Wordpress Scan ▏ 1526 ████████ (  7.7%)
      HTTP Crawl Non Statics ▏ 1098 ██████ (  5.5%)
            HTTP CVE Probing ▏  802 ████ (  4.0%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.5%)
       CVE-2017-9841 Exploit ▏  580 ███ (  2.9%)
   CVE-2018-20062 (Thinkphp) ▏  240 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  236 █ (  1.2%)
                 Netgear RCE ▏  164 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   95 █ (  0.5%)
 HTTP Path Traversal Probing ▏   88 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6627 ███████████████████████████████████ ( 41.1%)
United Kingdom ▏ 1855 █████████ ( 11.5%)
   Netherlands ▏ 1489 ███████ (  9.2%)
       Ireland ▏ 1281 ██████ (  7.9%)
        France ▏ 1183 ██████ (  7.3%)
     Singapore ▏  856 ████ (  5.3%)
        Canada ▏  786 ████ (  4.9%)
         Japan ▏  761 ████ (  4.7%)
       Germany ▏  707 ███ (  4.4%)
      Bulgaria ▏  576 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-05 ▏   33 ████████████████████ ( 12.4%)
2026-09-06 ▏   45 ███████████████████████████ ( 16.9%)
2026-09-07 ▏   57 ███████████████████████████████████ ( 21.3%)
2026-09-08 ▏   26 ███████████████ (  9.7%)
2026-09-09 ▏   39 ███████████████████████ ( 14.6%)
2026-09-10 ▏   31 ███████████████████ ( 11.6%)
2026-09-11 ▏   33 ████████████████████ ( 12.4%)
2026-09-12 ▏    3 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!