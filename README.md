# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-441-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 441                      |
| Total Reports: 14,258                |
| Unique Sources: 3,791                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4231 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2761 ██████████████████████ ( 19.5%)
HTTP Admin Interface Probing ▏ 1792 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 1343 ███████████ (  9.5%)
         HTTP Wordpress Scan ▏ 1246 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  722 █████ (  5.1%)
     HTTP Backdoors Attempts ▏  599 ████ (  4.2%)
            HTTP CVE Probing ▏  493 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  441 ███ (  3.1%)
      CVE-2022-41082 Exploit ▏  152 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.0%)
                 Netgear RCE ▏  109 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   50 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   47 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4345 ███████████████████████████████████ ( 36.7%)
United Kingdom ▏ 1765 ██████████████ ( 14.9%)
       Ireland ▏ 1217 █████████ ( 10.3%)
   Netherlands ▏  854 ██████ (  7.2%)
        France ▏  745 ██████ (  6.3%)
     Singapore ▏  692 █████ (  5.8%)
         Japan ▏  690 █████ (  5.8%)
        Canada ▏  523 ████ (  4.4%)
       Germany ▏  506 ████ (  4.3%)
     Australia ▏  495 ███ (  4.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-09 ▏   41 ███████████████████ ( 12.0%)
2026-04-10 ▏   35 ████████████████ ( 10.2%)
2026-04-11 ▏   55 █████████████████████████ ( 16.1%)
2026-04-12 ▏   75 ███████████████████████████████████ ( 21.9%)
2026-04-13 ▏   39 ██████████████████ ( 11.4%)
2026-04-14 ▏   33 ███████████████ (  9.6%)
2026-04-15 ▏   61 ████████████████████████████ ( 17.8%)
2026-04-16 ▏    3 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!