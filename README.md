# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-417-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--11-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 417                      |
| Total Reports: 1,130                 |
| Unique Sources: 474                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  314 ███████████████████████████████████ ( 27.9%)
                HTTP Probing ▏  279 ███████████████████████████████ ( 24.8%)
HTTP Admin Interface Probing ▏  114 ████████████ ( 10.1%)
        HTTP Sensitive Files ▏   88 █████████ (  7.8%)
         HTTP Wordpress Scan ▏   71 ███████ (  6.3%)
       CVE-2017-9841 Exploit ▏   65 ███████ (  5.8%)
      HTTP Crawl Non Statics ▏   52 █████ (  4.6%)
     HTTP Backdoors Attempts ▏   39 ████ (  3.5%)
            HTTP CVE Probing ▏   38 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏   27 ███ (  2.4%)
      CVE-2022-41082 Exploit ▏   14 █ (  1.2%)
 HTTP Path Traversal Probing ▏    9 █ (  0.8%)
                 Netgear RCE ▏    7 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  340 ███████████████████████████████████ ( 33.4%)
United Kingdom ▏  247 █████████████████████████ ( 24.2%)
       Ireland ▏  210 █████████████████████ ( 20.6%)
   Netherlands ▏   45 ████ (  4.4%)
     Singapore ▏   41 ████ (  4.0%)
         Japan ▏   35 ███ (  3.4%)
       Germany ▏   29 ██ (  2.8%)
         China ▏   26 ██ (  2.6%)
      Bulgaria ▏   26 ██ (  2.6%)
         India ▏   20 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-04 ▏   36 █████████████ (  8.5%)
2025-07-05 ▏   62 ███████████████████████ ( 14.6%)
2025-07-06 ▏   45 █████████████████ ( 10.6%)
2025-07-07 ▏   64 ████████████████████████ ( 15.1%)
2025-07-08 ▏   91 ███████████████████████████████████ ( 21.4%)
2025-07-09 ▏   65 █████████████████████████ ( 15.3%)
2025-07-10 ▏   59 ██████████████████████ ( 13.9%)
2025-07-11 ▏    3 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!