# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-529-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 529                      |
| Total Reports: 7,160                 |
| Unique Sources: 2,046                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1976 ███████████████████████████████████ ( 27.8%)
         HTTP Bad User Agent ▏ 1571 ███████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  777 █████████████ ( 10.9%)
        HTTP Sensitive Files ▏  733 ████████████ ( 10.3%)
         HTTP Wordpress Scan ▏  489 ████████ (  6.9%)
       CVE-2017-9841 Exploit ▏  342 ██████ (  4.8%)
      HTTP Crawl Non Statics ▏  321 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  299 █████ (  4.2%)
            HTTP CVE Probing ▏  260 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.8%)
      CVE-2022-41082 Exploit ▏   74 █ (  1.0%)
                 Netgear RCE ▏   60 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   25 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2117 ███████████████████████████████████ ( 34.4%)
United Kingdom ▏ 1143 ██████████████████ ( 18.6%)
       Ireland ▏  792 █████████████ ( 12.9%)
        France ▏  413 ██████ (  6.7%)
   Netherlands ▏  394 ██████ (  6.4%)
     Singapore ▏  315 █████ (  5.1%)
         Japan ▏  309 █████ (  5.0%)
     Australia ▏  272 ████ (  4.4%)
       Germany ▏  217 ███ (  3.5%)
         India ▏  184 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-19 ▏   64 ████████████████████████████ ( 12.9%)
2025-10-20 ▏   54 ███████████████████████ ( 10.9%)
2025-10-21 ▏   76 █████████████████████████████████ ( 15.3%)
2025-10-22 ▏   73 ███████████████████████████████ ( 14.7%)
2025-10-23 ▏   80 ███████████████████████████████████ ( 16.1%)
2025-10-24 ▏   76 █████████████████████████████████ ( 15.3%)
2025-10-25 ▏   66 ████████████████████████████ ( 13.3%)
2025-10-26 ▏    7 ███ (  1.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!