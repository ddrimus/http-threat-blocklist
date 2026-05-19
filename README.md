# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-481-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 481                      |
| Total Reports: 16,072                |
| Unique Sources: 4,254                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4773 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2984 █████████████████████ ( 18.7%)
HTTP Admin Interface Probing ▏ 2089 ███████████████ ( 13.1%)
        HTTP Sensitive Files ▏ 1571 ███████████ (  9.8%)
         HTTP Wordpress Scan ▏ 1408 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  862 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  665 ████ (  4.2%)
            HTTP CVE Probing ▏  581 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  450 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏  171 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.9%)
                 Netgear RCE ▏  128 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   62 █ (  0.4%)
 HTTP Path Traversal Probing ▏   59 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   50 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5070 ███████████████████████████████████ ( 38.5%)
United Kingdom ▏ 1779 ████████████ ( 13.5%)
       Ireland ▏ 1273 ████████ (  9.7%)
   Netherlands ▏  947 ██████ (  7.2%)
        France ▏  868 █████ (  6.6%)
     Singapore ▏  755 █████ (  5.7%)
         Japan ▏  714 ████ (  5.4%)
        Canada ▏  673 ████ (  5.1%)
       Germany ▏  596 ████ (  4.5%)
     Australia ▏  507 ███ (  3.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-12 ▏   48 ████████████████████████ ( 13.2%)
2026-05-13 ▏   47 ███████████████████████ ( 12.9%)
2026-05-14 ▏   59 █████████████████████████████ ( 16.2%)
2026-05-15 ▏   29 ██████████████ (  7.9%)
2026-05-16 ▏   54 ███████████████████████████ ( 14.8%)
2026-05-17 ▏   55 ███████████████████████████ ( 15.1%)
2026-05-18 ▏   70 ███████████████████████████████████ ( 19.2%)
2026-05-19 ▏    3 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!