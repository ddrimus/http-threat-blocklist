# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-343-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 343                      |
| Total Reports: 11,717                |
| Unique Sources: 3,177                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3433 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2496 █████████████████████████ ( 21.4%)
HTTP Admin Interface Probing ▏ 1350 █████████████ ( 11.6%)
        HTTP Sensitive Files ▏ 1235 ████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  836 ████████ (  7.2%)
      HTTP Crawl Non Statics ▏  501 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  488 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  427 ████ (  3.7%)
            HTTP CVE Probing ▏  410 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  122 █ (  1.0%)
                 Netgear RCE ▏   94 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   42 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3611 ███████████████████████████████████ ( 36.0%)
United Kingdom ▏ 1752 ████████████████ ( 17.5%)
       Ireland ▏ 1072 ██████████ ( 10.7%)
   Netherlands ▏  742 ███████ (  7.4%)
     Singapore ▏  578 █████ (  5.8%)
        France ▏  578 █████ (  5.8%)
         Japan ▏  576 █████ (  5.7%)
       Germany ▏  390 ███ (  3.9%)
     Australia ▏  379 ███ (  3.8%)
         India ▏  341 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-07 ▏   16 █████████ (  5.4%)
2026-02-08 ▏   38 █████████████████████ ( 12.8%)
2026-02-09 ▏   39 ██████████████████████ ( 13.1%)
2026-02-10 ▏   61 ███████████████████████████████████ ( 20.5%)
2026-02-11 ▏   43 ████████████████████████ ( 14.5%)
2026-02-12 ▏   60 ██████████████████████████████████ ( 20.2%)
2026-02-13 ▏   39 ██████████████████████ ( 13.1%)
2026-02-14 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!