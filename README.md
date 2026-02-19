# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-356-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 356                      |
| Total Reports: 11,856                |
| Unique Sources: 3,208                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3473 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2518 █████████████████████████ ( 21.3%)
HTTP Admin Interface Probing ▏ 1367 █████████████ ( 11.6%)
        HTTP Sensitive Files ▏ 1244 ████████████ ( 10.5%)
         HTTP Wordpress Scan ▏  859 ████████ (  7.3%)
      HTTP Crawl Non Statics ▏  513 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  493 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  427 ████ (  3.6%)
            HTTP CVE Probing ▏  417 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  124 █ (  1.1%)
                 Netgear RCE ▏   96 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   42 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3659 ███████████████████████████████████ ( 36.1%)
United Kingdom ▏ 1753 ████████████████ ( 17.3%)
       Ireland ▏ 1086 ██████████ ( 10.7%)
   Netherlands ▏  753 ███████ (  7.4%)
     Singapore ▏  584 █████ (  5.8%)
         Japan ▏  584 █████ (  5.8%)
        France ▏  578 █████ (  5.7%)
       Germany ▏  398 ███ (  3.9%)
     Australia ▏  381 ███ (  3.8%)
         India ▏  351 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-12 ▏   60 ███████████████████████████████████ ( 25.1%)
2026-02-13 ▏   39 ██████████████████████ ( 16.3%)
2026-02-14 ▏   35 ████████████████████ ( 14.6%)
2026-02-15 ▏   12 ███████ (  5.0%)
2026-02-16 ▏   30 █████████████████ ( 12.6%)
2026-02-17 ▏   28 ████████████████ ( 11.7%)
2026-02-18 ▏   32 ██████████████████ ( 13.4%)
2026-02-19 ▏    3 █ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!