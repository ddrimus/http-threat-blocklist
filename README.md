# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-268-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--07--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 268                      |
| Total Reports: 18,311                |
| Unique Sources: 4,843                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5493 ███████████████████████████████████ ( 30.2%)
         HTTP Bad User Agent ▏ 3313 █████████████████████ ( 18.2%)
HTTP Admin Interface Probing ▏ 2332 ██████████████ ( 12.8%)
        HTTP Sensitive Files ▏ 1988 ████████████ ( 10.9%)
         HTTP Wordpress Scan ▏ 1503 █████████ (  8.3%)
      HTTP Crawl Non Statics ▏ 1015 ██████ (  5.6%)
            HTTP CVE Probing ▏  694 ████ (  3.8%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.8%)
       CVE-2017-9841 Exploit ▏  460 ██ (  2.5%)
      CVE-2022-41082 Exploit ▏  212 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  146 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   84 █ (  0.5%)
 HTTP Path Traversal Probing ▏   68 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   59 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5996 ███████████████████████████████████ ( 40.2%)
United Kingdom ▏ 1811 ██████████ ( 12.1%)
   Netherlands ▏ 1300 ███████ (  8.7%)
       Ireland ▏ 1281 ███████ (  8.6%)
        France ▏ 1056 ██████ (  7.1%)
     Singapore ▏  805 ████ (  5.4%)
        Canada ▏  769 ████ (  5.2%)
         Japan ▏  727 ████ (  4.9%)
       Germany ▏  649 ███ (  4.4%)
     Australia ▏  516 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-07-12 ▏   29 ███████████████████████████████████ ( 19.9%)
2026-07-13 ▏   17 ████████████████████ ( 11.6%)
2026-07-14 ▏   20 ████████████████████████ ( 13.7%)
2026-07-15 ▏   19 ██████████████████████ ( 13.0%)
2026-07-16 ▏   17 ████████████████████ ( 11.6%)
2026-07-17 ▏   15 ██████████████████ ( 10.3%)
2026-07-18 ▏   28 █████████████████████████████████ ( 19.2%)
2026-07-19 ▏    1 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!