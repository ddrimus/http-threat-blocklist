# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-458-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--17-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 458                      |
| Total Reports: 14,331                |
| Unique Sources: 3,818                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4252 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2769 ██████████████████████ ( 19.4%)
HTTP Admin Interface Probing ▏ 1798 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 1349 ███████████ (  9.5%)
         HTTP Wordpress Scan ▏ 1255 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  730 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  606 ████ (  4.2%)
            HTTP CVE Probing ▏  497 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  441 ███ (  3.1%)
      CVE-2022-41082 Exploit ▏  154 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.0%)
                 Netgear RCE ▏  111 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   50 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   47 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4369 ███████████████████████████████████ ( 36.8%)
United Kingdom ▏ 1765 ██████████████ ( 14.9%)
       Ireland ▏ 1221 █████████ ( 10.3%)
   Netherlands ▏  856 ██████ (  7.2%)
        France ▏  758 ██████ (  6.4%)
     Singapore ▏  692 █████ (  5.8%)
         Japan ▏  690 █████ (  5.8%)
        Canada ▏  528 ████ (  4.4%)
       Germany ▏  507 ████ (  4.3%)
     Australia ▏  495 ███ (  4.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-10 ▏   35 ████████████████ (  9.4%)
2026-04-11 ▏   55 █████████████████████████ ( 14.7%)
2026-04-12 ▏   75 ██████████████████████████████████ ( 20.1%)
2026-04-13 ▏   39 █████████████████ ( 10.4%)
2026-04-14 ▏   33 ███████████████ (  8.8%)
2026-04-15 ▏   61 ████████████████████████████ ( 16.3%)
2026-04-16 ▏   76 ███████████████████████████████████ ( 20.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!