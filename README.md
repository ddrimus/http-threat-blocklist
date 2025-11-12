# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-569-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 569                      |
| Total Reports: 8,179                 |
| Unique Sources: 2,278                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2319 ███████████████████████████████████ ( 28.5%)
         HTTP Bad User Agent ▏ 1800 ███████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  888 █████████████ ( 10.9%)
        HTTP Sensitive Files ▏  879 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  540 ████████ (  6.6%)
       CVE-2017-9841 Exploit ▏  354 █████ (  4.4%)
      HTTP Crawl Non Statics ▏  352 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  339 █████ (  4.2%)
            HTTP CVE Probing ▏  289 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  128 █ (  1.6%)
      CVE-2022-41082 Exploit ▏   83 █ (  1.0%)
                 Netgear RCE ▏   67 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   29 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   28 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2423 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏ 1345 ███████████████████ ( 19.1%)
       Ireland ▏  855 ████████████ ( 12.1%)
   Netherlands ▏  516 ███████ (  7.3%)
        France ▏  442 ██████ (  6.3%)
         Japan ▏  403 █████ (  5.7%)
     Singapore ▏  327 ████ (  4.6%)
     Australia ▏  278 ████ (  3.9%)
       Germany ▏  252 ███ (  3.6%)
         India ▏  219 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-05 ▏   57 ██████████████████████ ( 12.8%)
2025-11-06 ▏   45 █████████████████ ( 10.1%)
2025-11-07 ▏   68 ██████████████████████████ ( 15.2%)
2025-11-08 ▏   89 ███████████████████████████████████ ( 19.9%)
2025-11-09 ▏   65 █████████████████████████ ( 14.5%)
2025-11-10 ▏   63 ████████████████████████ ( 14.1%)
2025-11-11 ▏   57 ██████████████████████ ( 12.8%)
2025-11-12 ▏    3 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!