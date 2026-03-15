# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-371-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--15-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 371                      |
| Total Reports: 12,729                |
| Unique Sources: 3,395                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3762 ███████████████████████████████████ ( 29.7%)
         HTTP Bad User Agent ▏ 2604 ████████████████████████ ( 20.5%)
HTTP Admin Interface Probing ▏ 1528 ██████████████ ( 12.0%)
        HTTP Sensitive Files ▏ 1267 ███████████ ( 10.0%)
         HTTP Wordpress Scan ▏ 1021 █████████ (  8.1%)
      HTTP Crawl Non Statics ▏  571 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  531 ████ (  4.2%)
            HTTP CVE Probing ▏  442 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  435 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  134 █ (  1.1%)
                 Netgear RCE ▏  103 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   52 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.4%)
 HTTP Path Traversal Probing ▏   43 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3904 ███████████████████████████████████ ( 36.5%)
United Kingdom ▏ 1754 ███████████████ ( 16.4%)
       Ireland ▏ 1133 ██████████ ( 10.6%)
   Netherlands ▏  800 ███████ (  7.5%)
     Singapore ▏  648 █████ (  6.1%)
         Japan ▏  648 █████ (  6.1%)
        France ▏  614 █████ (  5.7%)
       Germany ▏  410 ███ (  3.8%)
     Australia ▏  409 ███ (  3.8%)
         India ▏  364 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-08 ▏   29 ██████████████████████ ( 13.4%)
2026-03-09 ▏   16 ████████████ (  7.4%)
2026-03-10 ▏   23 █████████████████ ( 10.6%)
2026-03-11 ▏   21 ████████████████ (  9.7%)
2026-03-12 ▏   40 ███████████████████████████████ ( 18.5%)
2026-03-13 ▏   45 ███████████████████████████████████ ( 20.8%)
2026-03-14 ▏   38 █████████████████████████████ ( 17.6%)
2026-03-15 ▏    4 ███ (  1.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!