# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-394-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--07--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 394                      |
| Total Reports: 17,958                |
| Unique Sources: 4,764                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5363 ███████████████████████████████████ ( 30.0%)
         HTTP Bad User Agent ▏ 3263 █████████████████████ ( 18.3%)
HTTP Admin Interface Probing ▏ 2304 ███████████████ ( 12.9%)
        HTTP Sensitive Files ▏ 1906 ████████████ ( 10.7%)
         HTTP Wordpress Scan ▏ 1496 █████████ (  8.4%)
      HTTP Crawl Non Statics ▏ 1003 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.8%)
            HTTP CVE Probing ▏  673 ████ (  3.8%)
       CVE-2017-9841 Exploit ▏  458 ██ (  2.6%)
      CVE-2022-41082 Exploit ▏  205 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  142 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   82 █ (  0.5%)
 HTTP Path Traversal Probing ▏   67 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   57 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5890 ███████████████████████████████████ ( 40.3%)
United Kingdom ▏ 1809 ██████████ ( 12.4%)
       Ireland ▏ 1281 ███████ (  8.8%)
   Netherlands ▏ 1195 ███████ (  8.2%)
        France ▏  999 █████ (  6.8%)
     Singapore ▏  798 ████ (  5.5%)
        Canada ▏  768 ████ (  5.3%)
         Japan ▏  727 ████ (  5.0%)
       Germany ▏  643 ███ (  4.4%)
     Australia ▏  516 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-25 ▏   15 █████████████████ ( 10.3%)
2026-06-26 ▏   21 ████████████████████████ ( 14.4%)
2026-06-27 ▏   13 ███████████████ (  8.9%)
2026-06-28 ▏   25 █████████████████████████████ ( 17.1%)
2026-06-29 ▏   30 ███████████████████████████████████ ( 20.5%)
2026-06-30 ▏   14 ████████████████ (  9.6%)
2026-07-01 ▏   28 ████████████████████████████████ ( 19.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!