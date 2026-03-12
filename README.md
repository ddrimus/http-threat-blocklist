# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-365-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 365                      |
| Total Reports: 12,606                |
| Unique Sources: 3,369                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3722 ███████████████████████████████████ ( 29.6%)
         HTTP Bad User Agent ▏ 2590 ████████████████████████ ( 20.6%)
HTTP Admin Interface Probing ▏ 1505 ██████████████ ( 12.0%)
        HTTP Sensitive Files ▏ 1263 ███████████ ( 10.1%)
         HTTP Wordpress Scan ▏  998 █████████ (  7.9%)
      HTTP Crawl Non Statics ▏  562 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  528 ████ (  4.2%)
            HTTP CVE Probing ▏  439 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  435 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  133 █ (  1.1%)
                 Netgear RCE ▏  102 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   52 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3867 ███████████████████████████████████ ( 36.5%)
United Kingdom ▏ 1754 ███████████████ ( 16.5%)
       Ireland ▏ 1131 ██████████ ( 10.7%)
   Netherlands ▏  796 ███████ (  7.5%)
         Japan ▏  642 █████ (  6.1%)
     Singapore ▏  633 █████ (  6.0%)
        France ▏  604 █████ (  5.7%)
     Australia ▏  409 ███ (  3.9%)
       Germany ▏  406 ███ (  3.8%)
         India ▏  362 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-05 ▏   23 █████████████████ ( 11.4%)
2026-03-06 ▏   37 ███████████████████████████ ( 18.3%)
2026-03-07 ▏   47 ███████████████████████████████████ ( 23.3%)
2026-03-08 ▏   31 ███████████████████████ ( 15.3%)
2026-03-09 ▏   16 ███████████ (  7.9%)
2026-03-10 ▏   23 █████████████████ ( 11.4%)
2026-03-11 ▏   21 ███████████████ ( 10.4%)
2026-03-12 ▏    4 ██ (  2.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!