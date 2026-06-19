# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-550-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 550                      |
| Total Reports: 17,697                |
| Unique Sources: 4,703                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5279 ███████████████████████████████████ ( 30.0%)
         HTTP Bad User Agent ▏ 3210 █████████████████████ ( 18.2%)
HTTP Admin Interface Probing ▏ 2276 ███████████████ ( 12.9%)
        HTTP Sensitive Files ▏ 1854 ████████████ ( 10.5%)
         HTTP Wordpress Scan ▏ 1491 █████████ (  8.5%)
      HTTP Crawl Non Statics ▏  995 ██████ (  5.7%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.9%)
            HTTP CVE Probing ▏  656 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  458 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏  199 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  138 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   81 █ (  0.5%)
 HTTP Path Traversal Probing ▏   64 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   57 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5779 ███████████████████████████████████ ( 40.1%)
United Kingdom ▏ 1803 ██████████ ( 12.5%)
       Ireland ▏ 1281 ███████ (  8.9%)
   Netherlands ▏ 1146 ██████ (  7.9%)
        France ▏  973 █████ (  6.7%)
     Singapore ▏  791 ████ (  5.5%)
        Canada ▏  764 ████ (  5.3%)
         Japan ▏  726 ████ (  5.0%)
       Germany ▏  640 ███ (  4.4%)
     Australia ▏  516 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-12 ▏   46 ███████████████████████████ ( 13.9%)
2026-06-13 ▏   38 ██████████████████████ ( 11.4%)
2026-06-14 ▏   45 ██████████████████████████ ( 13.6%)
2026-06-15 ▏   59 ███████████████████████████████████ ( 17.8%)
2026-06-16 ▏   52 ██████████████████████████████ ( 15.7%)
2026-06-17 ▏   55 ████████████████████████████████ ( 16.6%)
2026-06-18 ▏   37 █████████████████████ ( 11.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!