# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-465-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 465                      |
| Total Reports: 14,395                |
| Unique Sources: 3,838                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4268 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2778 ██████████████████████ ( 19.4%)
HTTP Admin Interface Probing ▏ 1809 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 1353 ███████████ (  9.4%)
         HTTP Wordpress Scan ▏ 1264 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  737 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  610 █████ (  4.3%)
            HTTP CVE Probing ▏  499 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  441 ███ (  3.1%)
      CVE-2022-41082 Exploit ▏  154 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.0%)
                 Netgear RCE ▏  111 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   50 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   48 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4384 ███████████████████████████████████ ( 36.8%)
United Kingdom ▏ 1765 ██████████████ ( 14.8%)
       Ireland ▏ 1222 █████████ ( 10.3%)
   Netherlands ▏  862 ██████ (  7.2%)
        France ▏  761 ██████ (  6.4%)
     Singapore ▏  693 █████ (  5.8%)
         Japan ▏  690 █████ (  5.8%)
        Canada ▏  537 ████ (  4.5%)
       Germany ▏  507 ████ (  4.3%)
     Australia ▏  495 ███ (  4.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-11 ▏   55 █████████████████████████ ( 13.6%)
2026-04-12 ▏   75 ██████████████████████████████████ ( 18.6%)
2026-04-13 ▏   39 █████████████████ (  9.7%)
2026-04-14 ▏   33 ███████████████ (  8.2%)
2026-04-15 ▏   61 ████████████████████████████ ( 15.1%)
2026-04-16 ▏   76 ███████████████████████████████████ ( 18.9%)
2026-04-17 ▏   59 ███████████████████████████ ( 14.6%)
2026-04-18 ▏    5 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!