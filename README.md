# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-370-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--11-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 370                      |
| Total Reports: 12,586                |
| Unique Sources: 3,363                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3718 ███████████████████████████████████ ( 29.7%)
         HTTP Bad User Agent ▏ 2588 ████████████████████████ ( 20.6%)
HTTP Admin Interface Probing ▏ 1501 ██████████████ ( 12.0%)
        HTTP Sensitive Files ▏ 1263 ███████████ ( 10.1%)
         HTTP Wordpress Scan ▏  995 █████████ (  7.9%)
      HTTP Crawl Non Statics ▏  562 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  526 ████ (  4.2%)
            HTTP CVE Probing ▏  437 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  433 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  133 █ (  1.1%)
                 Netgear RCE ▏  102 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   52 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   44 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3862 ███████████████████████████████████ ( 36.5%)
United Kingdom ▏ 1754 ███████████████ ( 16.6%)
       Ireland ▏ 1131 ██████████ ( 10.7%)
   Netherlands ▏  796 ███████ (  7.5%)
         Japan ▏  639 █████ (  6.0%)
     Singapore ▏  633 █████ (  6.0%)
        France ▏  604 █████ (  5.7%)
       Germany ▏  406 ███ (  3.8%)
     Australia ▏  406 ███ (  3.8%)
         India ▏  362 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-04 ▏   29 █████████████████████ ( 13.6%)
2026-03-05 ▏   26 ███████████████████ ( 12.1%)
2026-03-06 ▏   37 ███████████████████████████ ( 17.3%)
2026-03-07 ▏   47 ███████████████████████████████████ ( 22.0%)
2026-03-08 ▏   31 ███████████████████████ ( 14.5%)
2026-03-09 ▏   16 ███████████ (  7.5%)
2026-03-10 ▏   23 █████████████████ ( 10.7%)
2026-03-11 ▏    5 ███ (  2.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!