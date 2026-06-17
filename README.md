# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-555-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--17-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 555                      |
| Total Reports: 17,610                |
| Unique Sources: 4,679                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5249 ███████████████████████████████████ ( 30.0%)
         HTTP Bad User Agent ▏ 3201 █████████████████████ ( 18.3%)
HTTP Admin Interface Probing ▏ 2268 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1842 ████████████ ( 10.5%)
         HTTP Wordpress Scan ▏ 1487 █████████ (  8.5%)
      HTTP Crawl Non Statics ▏  989 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.9%)
            HTTP CVE Probing ▏  650 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  458 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏  197 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  138 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   77 █ (  0.4%)
 HTTP Path Traversal Probing ▏   64 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   57 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5747 ███████████████████████████████████ ( 40.0%)
United Kingdom ▏ 1801 ██████████ ( 12.6%)
       Ireland ▏ 1281 ███████ (  8.9%)
   Netherlands ▏ 1122 ██████ (  7.8%)
        France ▏  963 █████ (  6.7%)
     Singapore ▏  791 ████ (  5.5%)
        Canada ▏  764 ████ (  5.3%)
         Japan ▏  726 ████ (  5.1%)
       Germany ▏  639 ███ (  4.5%)
     Australia ▏  516 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-10 ▏   38 ███████████████ ( 10.2%)
2026-06-11 ▏   87 ███████████████████████████████████ ( 23.5%)
2026-06-12 ▏   47 ██████████████████ ( 12.7%)
2026-06-13 ▏   38 ███████████████ ( 10.2%)
2026-06-14 ▏   45 ██████████████████ ( 12.1%)
2026-06-15 ▏   59 ███████████████████████ ( 15.9%)
2026-06-16 ▏   52 ████████████████████ ( 14.0%)
2026-06-17 ▏    5 ██ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!