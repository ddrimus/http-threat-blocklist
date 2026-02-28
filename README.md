# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-355-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--28-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 355                      |
| Total Reports: 12,187                |
| Unique Sources: 3,281                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3583 ███████████████████████████████████ ( 29.5%)
         HTTP Bad User Agent ▏ 2547 ████████████████████████ ( 21.0%)
HTTP Admin Interface Probing ▏ 1425 █████████████ ( 11.7%)
        HTTP Sensitive Files ▏ 1251 ████████████ ( 10.3%)
         HTTP Wordpress Scan ▏  917 ████████ (  7.6%)
      HTTP Crawl Non Statics ▏  540 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  511 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  429 ████ (  3.5%)
            HTTP CVE Probing ▏  428 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  128 █ (  1.1%)
                 Netgear RCE ▏  101 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   44 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3739 ███████████████████████████████████ ( 36.2%)
United Kingdom ▏ 1753 ████████████████ ( 17.0%)
       Ireland ▏ 1126 ██████████ ( 10.9%)
   Netherlands ▏  761 ███████ (  7.4%)
     Singapore ▏  612 █████ (  5.9%)
         Japan ▏  601 █████ (  5.8%)
        France ▏  590 █████ (  5.7%)
       Germany ▏  401 ███ (  3.9%)
     Australia ▏  398 ███ (  3.8%)
         India ▏  360 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-21 ▏   33 ███████████████████ ( 12.1%)
2026-02-22 ▏   46 ██████████████████████████ ( 16.8%)
2026-02-23 ▏   60 ███████████████████████████████████ ( 22.0%)
2026-02-24 ▏   41 ███████████████████████ ( 15.0%)
2026-02-25 ▏   26 ███████████████ (  9.5%)
2026-02-26 ▏   30 █████████████████ ( 11.0%)
2026-02-27 ▏   37 █████████████████████ ( 13.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!