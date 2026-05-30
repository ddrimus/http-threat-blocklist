# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-535-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 535                      |
| Total Reports: 16,756                |
| Unique Sources: 4,444                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4974 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 3078 █████████████████████ ( 18.5%)
HTTP Admin Interface Probing ▏ 2179 ███████████████ ( 13.1%)
        HTTP Sensitive Files ▏ 1675 ███████████ ( 10.1%)
         HTTP Wordpress Scan ▏ 1452 ██████████ (  8.7%)
      HTTP Crawl Non Statics ▏  925 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  679 ████ (  4.1%)
            HTTP CVE Probing ▏  610 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  454 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏  181 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.9%)
                 Netgear RCE ▏  132 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   68 █ (  0.4%)
 HTTP Path Traversal Probing ▏   61 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   52 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5390 ███████████████████████████████████ ( 39.3%)
United Kingdom ▏ 1789 ███████████ ( 13.1%)
       Ireland ▏ 1277 ████████ (  9.3%)
   Netherlands ▏ 1001 ██████ (  7.3%)
        France ▏  898 █████ (  6.6%)
     Singapore ▏  768 ████ (  5.6%)
        Canada ▏  736 ████ (  5.4%)
         Japan ▏  719 ████ (  5.2%)
       Germany ▏  619 ████ (  4.5%)
     Australia ▏  507 ███ (  3.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-23 ▏   38 ███████████████ (  9.3%)
2026-05-24 ▏   67 ██████████████████████████ ( 16.5%)
2026-05-25 ▏   36 ██████████████ (  8.8%)
2026-05-26 ▏   64 █████████████████████████ ( 15.7%)
2026-05-27 ▏   64 █████████████████████████ ( 15.7%)
2026-05-28 ▏   49 ███████████████████ ( 12.0%)
2026-05-29 ▏   87 ███████████████████████████████████ ( 21.4%)
2026-05-30 ▏    2 █ (  0.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!