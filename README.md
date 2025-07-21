# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-489-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 489                      |
| Total Reports: 1,950                 |
| Unique Sources: 702                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  479 ███████████████████████████████████ ( 24.7%)
                HTTP Probing ▏  478 ██████████████████████████████████ ( 24.6%)
HTTP Admin Interface Probing ▏  203 ██████████████ ( 10.5%)
        HTTP Sensitive Files ▏  162 ███████████ (  8.4%)
         HTTP Wordpress Scan ▏  141 ██████████ (  7.3%)
       CVE-2017-9841 Exploit ▏  119 ████████ (  6.1%)
     HTTP Backdoors Attempts ▏   96 ███████ (  4.9%)
      HTTP Crawl Non Statics ▏   94 ██████ (  4.8%)
   CVE-2018-20062 (Thinkphp) ▏   59 ████ (  3.0%)
            HTTP CVE Probing ▏   57 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   22 █ (  1.1%)
                 Netgear RCE ▏   11 █ (  0.6%)
 HTTP Path Traversal Probing ▏    9 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  538 ███████████████████████████████████ ( 31.0%)
United Kingdom ▏  406 ██████████████████████████ ( 23.4%)
       Ireland ▏  360 ███████████████████████ ( 20.7%)
   Netherlands ▏   84 █████ (  4.8%)
         Japan ▏   80 █████ (  4.6%)
     Singapore ▏   71 ████ (  4.1%)
     Australia ▏   68 ████ (  3.9%)
       Germany ▏   53 ███ (  3.1%)
         China ▏   42 ██ (  2.4%)
      Bulgaria ▏   35 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-14 ▏   52 █████████████████ (  8.8%)
2025-07-15 ▏  104 ██████████████████████████████████ ( 17.5%)
2025-07-16 ▏   88 █████████████████████████████ ( 14.8%)
2025-07-17 ▏   88 █████████████████████████████ ( 14.8%)
2025-07-18 ▏  105 ███████████████████████████████████ ( 17.7%)
2025-07-19 ▏   85 ████████████████████████████ ( 14.3%)
2025-07-20 ▏   66 ██████████████████████ ( 11.1%)
2025-07-21 ▏    6 ██ (  1.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!