# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-380-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 380                      |
| Total Reports: 12,544                |
| Unique Sources: 3,356                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3701 ███████████████████████████████████ ( 29.6%)
         HTTP Bad User Agent ▏ 2584 ████████████████████████ ( 20.7%)
HTTP Admin Interface Probing ▏ 1494 ██████████████ ( 12.0%)
        HTTP Sensitive Files ▏ 1260 ███████████ ( 10.1%)
         HTTP Wordpress Scan ▏  988 █████████ (  7.9%)
      HTTP Crawl Non Statics ▏  560 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  526 ████ (  4.2%)
            HTTP CVE Probing ▏  436 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  433 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  132 █ (  1.1%)
                 Netgear RCE ▏  102 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   52 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   44 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3850 ███████████████████████████████████ ( 36.5%)
United Kingdom ▏ 1754 ███████████████ ( 16.6%)
       Ireland ▏ 1129 ██████████ ( 10.7%)
   Netherlands ▏  789 ███████ (  7.5%)
     Singapore ▏  632 █████ (  6.0%)
         Japan ▏  630 █████ (  6.0%)
        France ▏  600 █████ (  5.7%)
     Australia ▏  406 ███ (  3.8%)
       Germany ▏  405 ███ (  3.8%)
         India ▏  362 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-02 ▏   46 █████████████████████████████████ ( 17.3%)
2026-03-03 ▏   48 ███████████████████████████████████ ( 18.0%)
2026-03-04 ▏   29 █████████████████████ ( 10.9%)
2026-03-05 ▏   26 ██████████████████ (  9.8%)
2026-03-06 ▏   37 ██████████████████████████ ( 13.9%)
2026-03-07 ▏   47 ██████████████████████████████████ ( 17.7%)
2026-03-08 ▏   31 ██████████████████████ ( 11.7%)
2026-03-09 ▏    2 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!