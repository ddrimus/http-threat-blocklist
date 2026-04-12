# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-432-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 432                      |
| Total Reports: 14,051                |
| Unique Sources: 3,728                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4167 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2733 ██████████████████████ ( 19.5%)
HTTP Admin Interface Probing ▏ 1760 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 1327 ███████████ (  9.5%)
         HTTP Wordpress Scan ▏ 1222 ██████████ (  8.7%)
      HTTP Crawl Non Statics ▏  703 █████ (  5.0%)
     HTTP Backdoors Attempts ▏  588 ████ (  4.2%)
            HTTP CVE Probing ▏  485 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  441 ███ (  3.2%)
      CVE-2022-41082 Exploit ▏  150 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.0%)
                 Netgear RCE ▏  108 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   48 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   47 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4287 ███████████████████████████████████ ( 36.7%)
United Kingdom ▏ 1762 ██████████████ ( 15.1%)
       Ireland ▏ 1212 █████████ ( 10.4%)
   Netherlands ▏  831 ██████ (  7.1%)
        France ▏  727 █████ (  6.2%)
     Singapore ▏  690 █████ (  5.9%)
         Japan ▏  677 █████ (  5.8%)
        Canada ▏  510 ████ (  4.4%)
       Germany ▏  499 ████ (  4.3%)
     Australia ▏  485 ███ (  4.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-05 ▏   39 █████████████████ ( 11.0%)
2026-04-06 ▏   47 ████████████████████ ( 13.2%)
2026-04-07 ▏   80 ███████████████████████████████████ ( 22.5%)
2026-04-08 ▏   55 ████████████████████████ ( 15.4%)
2026-04-09 ▏   41 █████████████████ ( 11.5%)
2026-04-10 ▏   35 ███████████████ (  9.8%)
2026-04-11 ▏   55 ████████████████████████ ( 15.4%)
2026-04-12 ▏    4 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!