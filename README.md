# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-491-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 491                      |
| Total Reports: 14,554                |
| Unique Sources: 3,885                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4317 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2804 ██████████████████████ ( 19.4%)
HTTP Admin Interface Probing ▏ 1833 ██████████████ ( 12.7%)
        HTTP Sensitive Files ▏ 1366 ███████████ (  9.4%)
         HTTP Wordpress Scan ▏ 1279 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  754 ██████ (  5.2%)
     HTTP Backdoors Attempts ▏  615 ████ (  4.2%)
            HTTP CVE Probing ▏  506 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  441 ███ (  3.0%)
      CVE-2022-41082 Exploit ▏  156 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.0%)
                 Netgear RCE ▏  112 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   50 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   48 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4439 ███████████████████████████████████ ( 36.9%)
United Kingdom ▏ 1770 █████████████ ( 14.7%)
       Ireland ▏ 1231 █████████ ( 10.2%)
   Netherlands ▏  871 ██████ (  7.2%)
        France ▏  772 ██████ (  6.4%)
     Singapore ▏  697 █████ (  5.8%)
         Japan ▏  690 █████ (  5.7%)
        Canada ▏  552 ████ (  4.6%)
       Germany ▏  518 ████ (  4.3%)
     Australia ▏  495 ███ (  4.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-14 ▏   31 ██████████████ (  7.9%)
2026-04-15 ▏   61 ████████████████████████████ ( 15.6%)
2026-04-16 ▏   76 ███████████████████████████████████ ( 19.4%)
2026-04-17 ▏   59 ███████████████████████████ ( 15.1%)
2026-04-18 ▏   63 █████████████████████████████ ( 16.1%)
2026-04-19 ▏   48 ██████████████████████ ( 12.3%)
2026-04-20 ▏   53 ████████████████████████ ( 13.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!