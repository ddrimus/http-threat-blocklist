# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-452-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 452                      |
| Total Reports: 10,000                |
| Unique Sources: 2,757                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2921 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2197 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1109 █████████████ ( 11.1%)
HTTP Admin Interface Probing ▏ 1083 ████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  636 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  420 █████ (  4.2%)
       CVE-2017-9841 Exploit ▏  400 ████ (  4.0%)
     HTTP Backdoors Attempts ▏  398 ████ (  4.0%)
            HTTP CVE Probing ▏  351 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  139 █ (  1.4%)
      CVE-2022-41082 Exploit ▏  100 █ (  1.0%)
                 Netgear RCE ▏   82 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3038 ███████████████████████████████████ ( 35.4%)
United Kingdom ▏ 1609 ██████████████████ ( 18.7%)
       Ireland ▏  972 ███████████ ( 11.3%)
   Netherlands ▏  657 ███████ (  7.7%)
         Japan ▏  488 █████ (  5.7%)
        France ▏  470 █████ (  5.5%)
     Singapore ▏  433 ████ (  5.0%)
     Australia ▏  333 ███ (  3.9%)
       Germany ▏  312 ███ (  3.6%)
      Bulgaria ▏  276 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-19 ▏   29 ████████████████████████ ( 12.4%)
2025-12-20 ▏   29 ████████████████████████ ( 12.4%)
2025-12-21 ▏   17 ██████████████ (  7.3%)
2025-12-22 ▏   36 ██████████████████████████████ ( 15.4%)
2025-12-23 ▏   41 ██████████████████████████████████ ( 17.5%)
2025-12-24 ▏   42 ███████████████████████████████████ ( 17.9%)
2025-12-25 ▏   36 ██████████████████████████████ ( 15.4%)
2025-12-26 ▏    4 ███ (  1.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!