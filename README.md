# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-543-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 543                      |
| Total Reports: 3,593                 |
| Unique Sources: 1,124                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  885 ███████████████████████████████████ ( 24.7%)
         HTTP Bad User Agent ▏  822 ████████████████████████████████ ( 23.0%)
HTTP Admin Interface Probing ▏  388 ███████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  299 ███████████ (  8.4%)
        HTTP Sensitive Files ▏  287 ███████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  237 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  178 ███████ (  5.0%)
      HTTP Crawl Non Statics ▏  165 ██████ (  4.6%)
            HTTP CVE Probing ▏  115 ████ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  107 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   31 █ (  0.9%)
                 Netgear RCE ▏   24 █ (  0.7%)
 HTTP Path Traversal Probing ▏   21 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   10 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  970 ███████████████████████████████████ ( 31.1%)
United Kingdom ▏  580 ████████████████████ ( 18.6%)
       Ireland ▏  521 ██████████████████ ( 16.7%)
         Japan ▏  219 ███████ (  7.0%)
     Australia ▏  213 ███████ (  6.8%)
     Singapore ▏  179 ██████ (  5.7%)
        France ▏  138 ████ (  4.4%)
   Netherlands ▏  120 ████ (  3.8%)
       Germany ▏   94 ███ (  3.0%)
         China ▏   88 ███ (  2.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-13 ▏   46 █████████████████ ( 13.2%)
2025-08-14 ▏   53 ████████████████████ ( 15.2%)
2025-08-15 ▏   91 ███████████████████████████████████ ( 26.1%)
2025-08-16 ▏   86 █████████████████████████████████ ( 24.6%)
2025-08-17 ▏   67 █████████████████████████ ( 19.2%)
2025-08-18 ▏    6 ██ (  1.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!