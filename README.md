# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-287-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 287                      |
| Total Reports: 19,078                |
| Unique Sources: 5,023                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5741 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3414 ████████████████████ ( 18.0%)
HTTP Admin Interface Probing ▏ 2397 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2126 ████████████ ( 11.2%)
         HTTP Wordpress Scan ▏ 1521 █████████ (  8.0%)
      HTTP Crawl Non Statics ▏ 1062 ██████ (  5.6%)
            HTTP CVE Probing ▏  738 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  494 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏  222 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  172 █ (  0.9%)
                 Netgear RCE ▏  156 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   91 █ (  0.5%)
 HTTP Path Traversal Probing ▏   72 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   61 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6306 ███████████████████████████████████ ( 40.6%)
United Kingdom ▏ 1839 ██████████ ( 11.8%)
   Netherlands ▏ 1423 ███████ (  9.2%)
       Ireland ▏ 1281 ███████ (  8.3%)
        France ▏ 1152 ██████ (  7.4%)
     Singapore ▏  821 ████ (  5.3%)
        Canada ▏  775 ████ (  5.0%)
         Japan ▏  736 ████ (  4.7%)
       Germany ▏  669 ███ (  4.3%)
     Australia ▏  517 ██ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-07 ▏   23 █████████████████████ ( 12.2%)
2026-08-08 ▏   21 ███████████████████ ( 11.1%)
2026-08-09 ▏   20 ██████████████████ ( 10.6%)
2026-08-10 ▏   26 ████████████████████████ ( 13.8%)
2026-08-11 ▏   37 ███████████████████████████████████ ( 19.6%)
2026-08-12 ▏   24 ██████████████████████ ( 12.7%)
2026-08-13 ▏   36 ██████████████████████████████████ ( 19.0%)
2026-08-14 ▏    2 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!