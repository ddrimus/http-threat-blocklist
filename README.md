# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-327-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 327                      |
| Total Reports: 11,617                |
| Unique Sources: 3,151                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3403 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2490 █████████████████████████ ( 21.5%)
HTTP Admin Interface Probing ▏ 1335 █████████████ ( 11.5%)
        HTTP Sensitive Files ▏ 1227 ████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  817 ████████ (  7.1%)
      HTTP Crawl Non Statics ▏  494 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  480 ████ (  4.1%)
       CVE-2017-9841 Exploit ▏  426 ████ (  3.7%)
            HTTP CVE Probing ▏  406 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  121 █ (  1.0%)
                 Netgear RCE ▏   94 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   41 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3582 ███████████████████████████████████ ( 36.0%)
United Kingdom ▏ 1750 █████████████████ ( 17.6%)
       Ireland ▏ 1063 ██████████ ( 10.7%)
   Netherlands ▏  734 ███████ (  7.4%)
         Japan ▏  576 █████ (  5.8%)
     Singapore ▏  573 █████ (  5.8%)
        France ▏  556 █████ (  5.6%)
       Germany ▏  390 ███ (  3.9%)
     Australia ▏  379 ███ (  3.8%)
         India ▏  341 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-05 ▏   41 ███████████████████████ ( 15.0%)
2026-02-06 ▏   35 ████████████████████ ( 12.8%)
2026-02-07 ▏   17 █████████ (  6.2%)
2026-02-08 ▏   38 █████████████████████ ( 13.9%)
2026-02-09 ▏   39 ██████████████████████ ( 14.2%)
2026-02-10 ▏   61 ███████████████████████████████████ ( 22.3%)
2026-02-11 ▏   43 ████████████████████████ ( 15.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!