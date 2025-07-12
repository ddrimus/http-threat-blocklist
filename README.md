# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-425-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 425                      |
| Total Reports: 1,212                 |
| Unique Sources: 497                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  329 ███████████████████████████████████ ( 27.2%)
                HTTP Probing ▏  301 ████████████████████████████████ ( 24.9%)
HTTP Admin Interface Probing ▏  122 ████████████ ( 10.1%)
        HTTP Sensitive Files ▏   98 ██████████ (  8.1%)
         HTTP Wordpress Scan ▏   78 ████████ (  6.5%)
       CVE-2017-9841 Exploit ▏   72 ███████ (  6.0%)
      HTTP Crawl Non Statics ▏   55 █████ (  4.6%)
     HTTP Backdoors Attempts ▏   45 ████ (  3.7%)
            HTTP CVE Probing ▏   40 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏   29 ███ (  2.4%)
      CVE-2022-41082 Exploit ▏   14 █ (  1.2%)
 HTTP Path Traversal Probing ▏    9 █ (  0.7%)
                 Netgear RCE ▏    7 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  355 ███████████████████████████████████ ( 32.4%)
United Kingdom ▏  264 ██████████████████████████ ( 24.1%)
       Ireland ▏  233 ██████████████████████ ( 21.3%)
   Netherlands ▏   51 █████ (  4.7%)
     Singapore ▏   43 ████ (  3.9%)
         Japan ▏   35 ███ (  3.2%)
       Germany ▏   31 ███ (  2.8%)
         China ▏   31 ███ (  2.8%)
      Bulgaria ▏   29 ██ (  2.6%)
         India ▏   24 ██ (  2.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-05 ▏   55 █████████████████████ ( 11.9%)
2025-07-06 ▏   45 █████████████████ (  9.7%)
2025-07-07 ▏   64 ████████████████████████ ( 13.8%)
2025-07-08 ▏   91 ███████████████████████████████████ ( 19.6%)
2025-07-09 ▏   65 █████████████████████████ ( 14.0%)
2025-07-10 ▏   59 ██████████████████████ ( 12.7%)
2025-07-11 ▏   72 ███████████████████████████ ( 15.5%)
2025-07-12 ▏   13 █████ (  2.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!