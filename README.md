# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-512-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--23-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 512                      |
| Total Reports: 6,933                 |
| Unique Sources: 2,002                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1899 ███████████████████████████████████ ( 27.6%)
         HTTP Bad User Agent ▏ 1537 ████████████████████████████ ( 22.3%)
HTTP Admin Interface Probing ▏  742 █████████████ ( 10.8%)
        HTTP Sensitive Files ▏  696 ████████████ ( 10.1%)
         HTTP Wordpress Scan ▏  478 ████████ (  6.9%)
       CVE-2017-9841 Exploit ▏  338 ██████ (  4.9%)
      HTTP Crawl Non Statics ▏  312 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  286 █████ (  4.2%)
            HTTP CVE Probing ▏  257 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.8%)
      CVE-2022-41082 Exploit ▏   72 █ (  1.0%)
                 Netgear RCE ▏   59 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   24 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2053 ███████████████████████████████████ ( 34.5%)
United Kingdom ▏ 1091 ██████████████████ ( 18.4%)
       Ireland ▏  768 █████████████ ( 12.9%)
        France ▏  409 ██████ (  6.9%)
   Netherlands ▏  368 ██████ (  6.2%)
     Singapore ▏  309 █████ (  5.2%)
         Japan ▏  284 ████ (  4.8%)
     Australia ▏  270 ████ (  4.5%)
       Germany ▏  215 ███ (  3.6%)
         India ▏  177 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-16 ▏   57 ██████████████████████████ ( 13.4%)
2025-10-17 ▏   48 ██████████████████████ ( 11.3%)
2025-10-18 ▏   47 █████████████████████ ( 11.0%)
2025-10-19 ▏   69 ███████████████████████████████ ( 16.2%)
2025-10-20 ▏   54 ████████████████████████ ( 12.7%)
2025-10-21 ▏   76 ███████████████████████████████████ ( 17.8%)
2025-10-22 ▏   73 █████████████████████████████████ ( 17.1%)
2025-10-23 ▏    2 █ (  0.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!