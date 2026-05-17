# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-492-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--17-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 492                      |
| Total Reports: 15,957                |
| Unique Sources: 4,231                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4739 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2971 █████████████████████ ( 18.7%)
HTTP Admin Interface Probing ▏ 2066 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1549 ███████████ (  9.8%)
         HTTP Wordpress Scan ▏ 1403 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  857 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  663 ████ (  4.2%)
            HTTP CVE Probing ▏  577 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  449 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏  169 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  145 █ (  0.9%)
                 Netgear RCE ▏  128 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   59 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   50 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5015 ███████████████████████████████████ ( 38.3%)
United Kingdom ▏ 1779 ████████████ ( 13.6%)
       Ireland ▏ 1273 ████████ (  9.7%)
   Netherlands ▏  938 ██████ (  7.2%)
        France ▏  868 ██████ (  6.6%)
     Singapore ▏  742 █████ (  5.7%)
         Japan ▏  711 ████ (  5.4%)
        Canada ▏  673 ████ (  5.1%)
       Germany ▏  575 ████ (  4.4%)
     Australia ▏  507 ███ (  3.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-10 ▏   61 ███████████████████████████████ ( 16.0%)
2026-05-11 ▏   68 ███████████████████████████████████ ( 17.8%)
2026-05-12 ▏   50 █████████████████████████ ( 13.1%)
2026-05-13 ▏   47 ████████████████████████ ( 12.3%)
2026-05-14 ▏   59 ██████████████████████████████ ( 15.5%)
2026-05-15 ▏   29 ██████████████ (  7.6%)
2026-05-16 ▏   54 ███████████████████████████ ( 14.2%)
2026-05-17 ▏   13 ██████ (  3.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!