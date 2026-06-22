# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-513-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--22-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 513                      |
| Total Reports: 17,764                |
| Unique Sources: 4,717                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5299 ███████████████████████████████████ ( 30.0%)
         HTTP Bad User Agent ▏ 3224 █████████████████████ ( 18.3%)
HTTP Admin Interface Probing ▏ 2284 ███████████████ ( 12.9%)
        HTTP Sensitive Files ▏ 1867 ████████████ ( 10.6%)
         HTTP Wordpress Scan ▏ 1493 █████████ (  8.5%)
      HTTP Crawl Non Statics ▏  998 ██████ (  5.7%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.9%)
            HTTP CVE Probing ▏  660 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  458 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏  200 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  139 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   81 █ (  0.5%)
 HTTP Path Traversal Probing ▏   65 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   57 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5799 ███████████████████████████████████ ( 40.1%)
United Kingdom ▏ 1804 ██████████ ( 12.5%)
       Ireland ▏ 1281 ███████ (  8.9%)
   Netherlands ▏ 1162 ███████ (  8.0%)
        France ▏  982 █████ (  6.8%)
     Singapore ▏  791 ████ (  5.5%)
        Canada ▏  764 ████ (  5.3%)
         Japan ▏  726 ████ (  5.0%)
       Germany ▏  643 ███ (  4.4%)
     Australia ▏  516 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-15 ▏   56 ███████████████████████████████████ ( 21.0%)
2026-06-16 ▏   52 ████████████████████████████████ ( 19.5%)
2026-06-17 ▏   55 ██████████████████████████████████ ( 20.6%)
2026-06-18 ▏   37 ███████████████████████ ( 13.9%)
2026-06-19 ▏   19 ███████████ (  7.1%)
2026-06-20 ▏   22 █████████████ (  8.2%)
2026-06-21 ▏   23 ██████████████ (  8.6%)
2026-06-22 ▏    3 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!