# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-345-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--01--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 345                      |
| Total Reports: 11,079                |
| Unique Sources: 3,020                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3244 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2422 ██████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏ 1243 █████████████ ( 11.3%)
        HTTP Sensitive Files ▏ 1209 █████████████ ( 11.0%)
         HTTP Wordpress Scan ▏  730 ███████ (  6.6%)
      HTTP Crawl Non Statics ▏  470 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  443 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  415 ████ (  3.8%)
            HTTP CVE Probing ▏  378 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  142 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  113 █ (  1.0%)
                 Netgear RCE ▏   90 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.5%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   40 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3426 ███████████████████████████████████ ( 36.0%)
United Kingdom ▏ 1714 █████████████████ ( 18.0%)
       Ireland ▏ 1022 ██████████ ( 10.7%)
   Netherlands ▏  724 ███████ (  7.6%)
        France ▏  535 █████ (  5.6%)
         Japan ▏  533 █████ (  5.6%)
     Singapore ▏  516 █████ (  5.4%)
       Germany ▏  383 ███ (  4.0%)
     Australia ▏  352 ███ (  3.7%)
         India ▏  311 ███ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-21 ▏   29 ████████████████████████ ( 13.2%)
2026-01-22 ▏   39 ████████████████████████████████ ( 17.7%)
2026-01-23 ▏   42 ███████████████████████████████████ ( 19.1%)
2026-01-24 ▏   24 ████████████████████ ( 10.9%)
2026-01-25 ▏   40 █████████████████████████████████ ( 18.2%)
2026-01-26 ▏   41 ██████████████████████████████████ ( 18.6%)
2026-01-27 ▏    5 ████ (  2.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!