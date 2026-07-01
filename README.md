# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-402-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--07--01-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 402                      |
| Total Reports: 17,930                |
| Unique Sources: 4,755                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5356 ███████████████████████████████████ ( 30.1%)
         HTTP Bad User Agent ▏ 3258 █████████████████████ ( 18.3%)
HTTP Admin Interface Probing ▏ 2300 ███████████████ ( 12.9%)
        HTTP Sensitive Files ▏ 1900 ████████████ ( 10.7%)
         HTTP Wordpress Scan ▏ 1496 █████████ (  8.4%)
      HTTP Crawl Non Statics ▏ 1002 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.8%)
            HTTP CVE Probing ▏  670 ████ (  3.8%)
       CVE-2017-9841 Exploit ▏  458 ██ (  2.6%)
      CVE-2022-41082 Exploit ▏  204 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  141 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   82 █ (  0.5%)
 HTTP Path Traversal Probing ▏   67 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   57 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5876 ███████████████████████████████████ ( 40.2%)
United Kingdom ▏ 1808 ██████████ ( 12.4%)
       Ireland ▏ 1281 ███████ (  8.8%)
   Netherlands ▏ 1194 ███████ (  8.2%)
        France ▏  999 █████ (  6.8%)
     Singapore ▏  797 ████ (  5.5%)
        Canada ▏  764 ████ (  5.2%)
         Japan ▏  727 ████ (  5.0%)
       Germany ▏  643 ███ (  4.4%)
     Australia ▏  516 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-24 ▏   19 ██████████████████████ ( 13.9%)
2026-06-25 ▏   15 █████████████████ ( 10.9%)
2026-06-26 ▏   21 ████████████████████████ ( 15.3%)
2026-06-27 ▏   13 ███████████████ (  9.5%)
2026-06-28 ▏   25 █████████████████████████████ ( 18.2%)
2026-06-29 ▏   30 ███████████████████████████████████ ( 21.9%)
2026-06-30 ▏   14 ████████████████ ( 10.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!