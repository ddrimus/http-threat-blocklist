# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-333-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--01--31-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 333                      |
| Total Reports: 11,199                |
| Unique Sources: 3,050                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3284 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2438 █████████████████████████ ( 21.9%)
HTTP Admin Interface Probing ▏ 1264 █████████████ ( 11.3%)
        HTTP Sensitive Files ▏ 1218 ████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  747 ███████ (  6.7%)
      HTTP Crawl Non Statics ▏  472 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  451 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  415 ████ (  3.7%)
            HTTP CVE Probing ▏  383 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  142 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  114 █ (  1.0%)
                 Netgear RCE ▏   91 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.5%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   40 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3449 ███████████████████████████████████ ( 35.9%)
United Kingdom ▏ 1734 █████████████████ ( 18.0%)
       Ireland ▏ 1030 ██████████ ( 10.7%)
   Netherlands ▏  726 ███████ (  7.5%)
         Japan ▏  551 █████ (  5.7%)
        France ▏  535 █████ (  5.6%)
     Singapore ▏  526 █████ (  5.5%)
       Germany ▏  385 ███ (  4.0%)
     Australia ▏  357 ███ (  3.7%)
         India ▏  327 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-24 ▏   21 █████████████████ (  9.3%)
2026-01-25 ▏   40 ██████████████████████████████████ ( 17.6%)
2026-01-26 ▏   41 ███████████████████████████████████ ( 18.1%)
2026-01-27 ▏   33 ████████████████████████████ ( 14.5%)
2026-01-28 ▏   23 ███████████████████ ( 10.1%)
2026-01-29 ▏   31 ██████████████████████████ ( 13.7%)
2026-01-30 ▏   33 ████████████████████████████ ( 14.5%)
2026-01-31 ▏    5 ████ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!