# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-395-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--28-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 395                      |
| Total Reports: 13,396                |
| Unique Sources: 3,534                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3968 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2655 ███████████████████████ ( 19.9%)
HTTP Admin Interface Probing ▏ 1660 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 1297 ███████████ (  9.7%)
         HTTP Wordpress Scan ▏ 1122 █████████ (  8.4%)
      HTTP Crawl Non Statics ▏  636 █████ (  4.8%)
     HTTP Backdoors Attempts ▏  549 ████ (  4.1%)
            HTTP CVE Probing ▏  462 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  440 ███ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  140 █ (  1.1%)
                 Netgear RCE ▏  104 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4113 ███████████████████████████████████ ( 36.7%)
United Kingdom ▏ 1758 ██████████████ ( 15.7%)
       Ireland ▏ 1172 █████████ ( 10.5%)
   Netherlands ▏  817 ██████ (  7.3%)
        France ▏  681 █████ (  6.1%)
     Singapore ▏  673 █████ (  6.0%)
         Japan ▏  671 █████ (  6.0%)
       Germany ▏  483 ████ (  4.3%)
     Australia ▏  421 ███ (  3.8%)
        Canada ▏  418 ███ (  3.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-21 ▏   32 ████████████████ (  8.4%)
2026-03-22 ▏   67 ███████████████████████████████████ ( 17.5%)
2026-03-23 ▏   47 ████████████████████████ ( 12.3%)
2026-03-24 ▏   59 ██████████████████████████████ ( 15.4%)
2026-03-25 ▏   55 ████████████████████████████ ( 14.4%)
2026-03-26 ▏   66 ██████████████████████████████████ ( 17.2%)
2026-03-27 ▏   52 ███████████████████████████ ( 13.6%)
2026-03-28 ▏    5 ██ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!