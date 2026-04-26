# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-487-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 487                      |
| Total Reports: 14,801                |
| Unique Sources: 3,966                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4390 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2833 ██████████████████████ ( 19.2%)
HTTP Admin Interface Probing ▏ 1864 ██████████████ ( 12.7%)
        HTTP Sensitive Files ▏ 1387 ███████████ (  9.4%)
         HTTP Wordpress Scan ▏ 1307 ██████████ (  8.9%)
      HTTP Crawl Non Statics ▏  782 ██████ (  5.3%)
     HTTP Backdoors Attempts ▏  629 █████ (  4.3%)
            HTTP CVE Probing ▏  519 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  442 ███ (  3.0%)
      CVE-2022-41082 Exploit ▏  162 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.0%)
                 Netgear RCE ▏  114 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   50 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   48 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4514 ███████████████████████████████████ ( 37.0%)
United Kingdom ▏ 1770 █████████████ ( 14.5%)
       Ireland ▏ 1255 █████████ ( 10.3%)
   Netherlands ▏  875 ██████ (  7.2%)
        France ▏  805 ██████ (  6.6%)
     Singapore ▏  705 █████ (  5.8%)
         Japan ▏  690 █████ (  5.7%)
        Canada ▏  555 ████ (  4.6%)
       Germany ▏  523 ████ (  4.3%)
     Australia ▏  499 ███ (  4.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-19 ▏   47 █████████████████████████████ ( 13.5%)
2026-04-20 ▏   53 █████████████████████████████████ ( 15.3%)
2026-04-21 ▏   39 ████████████████████████ ( 11.2%)
2026-04-22 ▏   55 ███████████████████████████████████ ( 15.9%)
2026-04-23 ▏   54 ██████████████████████████████████ ( 15.6%)
2026-04-24 ▏   39 ████████████████████████ ( 11.2%)
2026-04-25 ▏   53 █████████████████████████████████ ( 15.3%)
2026-04-26 ▏    7 ████ (  2.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!