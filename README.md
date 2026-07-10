# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-329-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--07--10-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 329                      |
| Total Reports: 18,109                |
| Unique Sources: 4,800                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5418 ███████████████████████████████████ ( 30.1%)
         HTTP Bad User Agent ▏ 3289 █████████████████████ ( 18.3%)
HTTP Admin Interface Probing ▏ 2319 ██████████████ ( 12.9%)
        HTTP Sensitive Files ▏ 1936 ████████████ ( 10.8%)
         HTTP Wordpress Scan ▏ 1499 █████████ (  8.3%)
      HTTP Crawl Non Statics ▏ 1007 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.8%)
            HTTP CVE Probing ▏  683 ████ (  3.8%)
       CVE-2017-9841 Exploit ▏  458 ██ (  2.5%)
      CVE-2022-41082 Exploit ▏  208 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  145 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   82 █ (  0.5%)
 HTTP Path Traversal Probing ▏   67 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   57 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5942 ███████████████████████████████████ ( 40.3%)
United Kingdom ▏ 1810 ██████████ ( 12.3%)
       Ireland ▏ 1281 ███████ (  8.7%)
   Netherlands ▏ 1235 ███████ (  8.4%)
        France ▏ 1018 █████ (  6.9%)
     Singapore ▏  804 ████ (  5.5%)
        Canada ▏  768 ████ (  5.2%)
         Japan ▏  727 ████ (  4.9%)
       Germany ▏  644 ███ (  4.4%)
     Australia ▏  516 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-07-03 ▏   11 ████████████ (  8.4%)
2026-07-04 ▏   13 ███████████████ (  9.9%)
2026-07-05 ▏   30 ███████████████████████████████████ ( 22.9%)
2026-07-06 ▏   14 ████████████████ ( 10.7%)
2026-07-07 ▏   21 ████████████████████████ ( 16.0%)
2026-07-08 ▏   21 ████████████████████████ ( 16.0%)
2026-07-09 ▏   19 ██████████████████████ ( 14.5%)
2026-07-10 ▏    2 ██ (  1.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!