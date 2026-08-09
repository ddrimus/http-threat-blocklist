# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-289-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 289                      |
| Total Reports: 18,937                |
| Unique Sources: 4,991                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5690 ███████████████████████████████████ ( 30.2%)
         HTTP Bad User Agent ▏ 3397 ████████████████████ ( 18.1%)
HTTP Admin Interface Probing ▏ 2385 ██████████████ ( 12.7%)
        HTTP Sensitive Files ▏ 2096 ████████████ ( 11.1%)
         HTTP Wordpress Scan ▏ 1519 █████████ (  8.1%)
      HTTP Crawl Non Statics ▏ 1058 ██████ (  5.6%)
            HTTP CVE Probing ▏  732 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  487 ██ (  2.6%)
      CVE-2022-41082 Exploit ▏  221 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  168 █ (  0.9%)
                 Netgear RCE ▏  155 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   90 █ (  0.5%)
 HTTP Path Traversal Probing ▏   70 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   60 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6263 ███████████████████████████████████ ( 40.7%)
United Kingdom ▏ 1836 ██████████ ( 11.9%)
   Netherlands ▏ 1381 ███████ (  9.0%)
       Ireland ▏ 1281 ███████ (  8.3%)
        France ▏ 1139 ██████ (  7.4%)
     Singapore ▏  818 ████ (  5.3%)
        Canada ▏  773 ████ (  5.0%)
         Japan ▏  731 ████ (  4.7%)
       Germany ▏  669 ███ (  4.3%)
     Australia ▏  516 ██ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-02 ▏   54 ███████████████████████████████████ ( 27.0%)
2026-08-03 ▏   24 ███████████████ ( 12.0%)
2026-08-04 ▏   30 ███████████████████ ( 15.0%)
2026-08-05 ▏   21 █████████████ ( 10.5%)
2026-08-06 ▏   18 ███████████ (  9.0%)
2026-08-07 ▏   28 ██████████████████ ( 14.0%)
2026-08-08 ▏   21 █████████████ ( 10.5%)
2026-08-09 ▏    4 ██ (  2.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!