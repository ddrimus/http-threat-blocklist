# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-277-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 277                      |
| Total Reports: 18,737                |
| Unique Sources: 4,940                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5623 ███████████████████████████████████ ( 30.2%)
         HTTP Bad User Agent ▏ 3375 █████████████████████ ( 18.1%)
HTTP Admin Interface Probing ▏ 2367 ██████████████ ( 12.7%)
        HTTP Sensitive Files ▏ 2065 ████████████ ( 11.1%)
         HTTP Wordpress Scan ▏ 1514 █████████ (  8.1%)
      HTTP Crawl Non Statics ▏ 1048 ██████ (  5.6%)
            HTTP CVE Probing ▏  721 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  472 ██ (  2.5%)
      CVE-2022-41082 Exploit ▏  219 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  154 █ (  0.8%)
                 Netgear RCE ▏  152 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   90 █ (  0.5%)
 HTTP Path Traversal Probing ▏   70 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   60 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6184 ███████████████████████████████████ ( 40.5%)
United Kingdom ▏ 1828 ██████████ ( 12.0%)
   Netherlands ▏ 1359 ███████ (  8.9%)
       Ireland ▏ 1281 ███████ (  8.4%)
        France ▏ 1126 ██████ (  7.4%)
     Singapore ▏  809 ████ (  5.3%)
        Canada ▏  772 ████ (  5.1%)
         Japan ▏  728 ████ (  4.8%)
       Germany ▏  655 ███ (  4.3%)
     Australia ▏  516 ██ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-07-26 ▏   22 ██████████████████ (  8.9%)
2026-07-27 ▏   17 ██████████████ (  6.9%)
2026-07-28 ▏   34 █████████████████████████████ ( 13.8%)
2026-07-29 ▏   34 █████████████████████████████ ( 13.8%)
2026-07-30 ▏   26 ██████████████████████ ( 10.6%)
2026-07-31 ▏   41 ███████████████████████████████████ ( 16.7%)
2026-08-01 ▏   40 ██████████████████████████████████ ( 16.3%)
2026-08-02 ▏   32 ███████████████████████████ ( 13.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!