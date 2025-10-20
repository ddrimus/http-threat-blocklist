# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-499-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 499                      |
| Total Reports: 6,731                 |
| Unique Sources: 1,949                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1828 ███████████████████████████████████ ( 27.3%)
         HTTP Bad User Agent ▏ 1500 ████████████████████████████ ( 22.4%)
HTTP Admin Interface Probing ▏  718 █████████████ ( 10.7%)
        HTTP Sensitive Files ▏  659 ████████████ (  9.9%)
         HTTP Wordpress Scan ▏  471 █████████ (  7.0%)
       CVE-2017-9841 Exploit ▏  337 ██████ (  5.0%)
      HTTP Crawl Non Statics ▏  309 █████ (  4.6%)
     HTTP Backdoors Attempts ▏  281 █████ (  4.2%)
            HTTP CVE Probing ▏  249 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.9%)
      CVE-2022-41082 Exploit ▏   71 █ (  1.1%)
                 Netgear RCE ▏   55 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2000 ███████████████████████████████████ ( 34.6%)
United Kingdom ▏ 1050 ██████████████████ ( 18.2%)
       Ireland ▏  763 █████████████ ( 13.2%)
        France ▏  399 ██████ (  6.9%)
   Netherlands ▏  332 █████ (  5.7%)
     Singapore ▏  306 █████ (  5.3%)
         Japan ▏  278 ████ (  4.8%)
     Australia ▏  267 ████ (  4.6%)
       Germany ▏  211 ███ (  3.7%)
      Bulgaria ▏  169 ██ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-13 ▏   72 █████████████████████████████████ ( 16.5%)
2025-10-14 ▏   58 ██████████████████████████ ( 13.3%)
2025-10-15 ▏   76 ███████████████████████████████████ ( 17.4%)
2025-10-16 ▏   63 █████████████████████████████ ( 14.4%)
2025-10-17 ▏   48 ██████████████████████ ( 11.0%)
2025-10-18 ▏   47 █████████████████████ ( 10.8%)
2025-10-19 ▏   69 ███████████████████████████████ ( 15.8%)
2025-10-20 ▏    3 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!