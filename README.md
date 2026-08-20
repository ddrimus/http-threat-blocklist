# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-292-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 292                      |
| Total Reports: 19,240                |
| Unique Sources: 5,067                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5791 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3436 ████████████████████ ( 18.0%)
HTTP Admin Interface Probing ▏ 2410 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2147 ████████████ ( 11.2%)
         HTTP Wordpress Scan ▏ 1523 █████████ (  8.0%)
      HTTP Crawl Non Statics ▏ 1067 ██████ (  5.6%)
            HTTP CVE Probing ▏  750 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  510 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏  224 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  184 █ (  1.0%)
                 Netgear RCE ▏  159 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   93 █ (  0.5%)
 HTTP Path Traversal Probing ▏   72 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   61 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6362 ███████████████████████████████████ ( 40.8%)
United Kingdom ▏ 1843 ██████████ ( 11.8%)
   Netherlands ▏ 1430 ███████ (  9.2%)
       Ireland ▏ 1281 ███████ (  8.2%)
        France ▏ 1157 ██████ (  7.4%)
     Singapore ▏  822 ████ (  5.3%)
        Canada ▏  775 ████ (  5.0%)
         Japan ▏  742 ████ (  4.8%)
       Germany ▏  681 ███ (  4.4%)
     Australia ▏  517 ██ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-13 ▏   31 ███████████████████████████ ( 15.9%)
2026-08-14 ▏   20 █████████████████ ( 10.3%)
2026-08-15 ▏   19 █████████████████ (  9.7%)
2026-08-16 ▏   12 ██████████ (  6.2%)
2026-08-17 ▏   39 ███████████████████████████████████ ( 20.0%)
2026-08-18 ▏   35 ███████████████████████████████ ( 17.9%)
2026-08-19 ▏   35 ███████████████████████████████ ( 17.9%)
2026-08-20 ▏    4 ███ (  2.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!