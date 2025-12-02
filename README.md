# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-543-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--02-brightgreen)](.)

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
| Total Reports: 9,196                 |
| Unique Sources: 2,535                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2649 ███████████████████████████████████ ( 29.0%)
         HTTP Bad User Agent ▏ 2013 ██████████████████████████ ( 22.0%)
        HTTP Sensitive Files ▏ 1026 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏  995 █████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  585 ███████ (  6.4%)
       CVE-2017-9841 Exploit ▏  384 █████ (  4.2%)
      HTTP Crawl Non Statics ▏  383 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  370 ████ (  4.0%)
            HTTP CVE Probing ▏  329 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  133 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   93 █ (  1.0%)
                 Netgear RCE ▏   76 █ (  0.8%)
 HTTP Path Traversal Probing ▏   40 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   38 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2734 ███████████████████████████████████ ( 34.7%)
United Kingdom ▏ 1501 ███████████████████ ( 19.1%)
       Ireland ▏  905 ███████████ ( 11.5%)
   Netherlands ▏  616 ███████ (  7.8%)
        France ▏  462 █████ (  5.9%)
         Japan ▏  453 █████ (  5.8%)
     Singapore ▏  373 ████ (  4.7%)
     Australia ▏  293 ███ (  3.7%)
       Germany ▏  284 ███ (  3.6%)
      Bulgaria ▏  249 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-25 ▏   80 ███████████████████████████████████ ( 23.1%)
2025-11-26 ▏   44 ███████████████████ ( 12.7%)
2025-11-27 ▏   46 ████████████████████ ( 13.3%)
2025-11-28 ▏   53 ███████████████████████ ( 15.3%)
2025-11-29 ▏   42 ██████████████████ ( 12.1%)
2025-11-30 ▏   34 ██████████████ (  9.8%)
2025-12-01 ▏   47 ████████████████████ ( 13.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!