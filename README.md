# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-436-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--28-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 436                      |
| Total Reports: 10,071                |
| Unique Sources: 2,778                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2939 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2213 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1115 █████████████ ( 11.1%)
HTTP Admin Interface Probing ▏ 1093 █████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  641 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  426 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  401 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  400 ████ (  4.0%)
            HTTP CVE Probing ▏  354 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  139 █ (  1.4%)
      CVE-2022-41082 Exploit ▏  101 █ (  1.0%)
                 Netgear RCE ▏   84 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   36 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3055 ███████████████████████████████████ ( 35.4%)
United Kingdom ▏ 1614 ██████████████████ ( 18.7%)
       Ireland ▏  977 ███████████ ( 11.3%)
   Netherlands ▏  661 ███████ (  7.7%)
         Japan ▏  489 █████ (  5.7%)
        France ▏  470 █████ (  5.4%)
     Singapore ▏  436 ████ (  5.0%)
     Australia ▏  333 ███ (  3.9%)
       Germany ▏  324 ███ (  3.8%)
      Bulgaria ▏  279 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-21 ▏   16 █████████████ (  6.5%)
2025-12-22 ▏   36 ██████████████████████████████ ( 14.6%)
2025-12-23 ▏   41 ██████████████████████████████████ ( 16.7%)
2025-12-24 ▏   42 ███████████████████████████████████ ( 17.1%)
2025-12-25 ▏   36 ██████████████████████████████ ( 14.6%)
2025-12-26 ▏   42 ███████████████████████████████████ ( 17.1%)
2025-12-27 ▏   31 █████████████████████████ ( 12.6%)
2025-12-28 ▏    2 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!