# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-353-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 353                      |
| Total Reports: 20,095                |
| Unique Sources: 5,302                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6057 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3515 ████████████████████ ( 17.6%)
HTTP Admin Interface Probing ▏ 2482 ██████████████ ( 12.4%)
        HTTP Sensitive Files ▏ 2277 █████████████ ( 11.4%)
         HTTP Wordpress Scan ▏ 1526 ████████ (  7.7%)
      HTTP Crawl Non Statics ▏ 1103 ██████ (  5.5%)
            HTTP CVE Probing ▏  808 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.4%)
       CVE-2017-9841 Exploit ▏  587 ███ (  2.9%)
   CVE-2018-20062 (Thinkphp) ▏  247 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  237 █ (  1.2%)
                 Netgear RCE ▏  166 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   95 █ (  0.5%)
 HTTP Path Traversal Probing ▏   91 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6655 ███████████████████████████████████ ( 41.2%)
United Kingdom ▏ 1857 █████████ ( 11.5%)
   Netherlands ▏ 1489 ███████ (  9.2%)
       Ireland ▏ 1281 ██████ (  7.9%)
        France ▏ 1183 ██████ (  7.3%)
     Singapore ▏  856 ████ (  5.3%)
        Canada ▏  786 ████ (  4.9%)
         Japan ▏  764 ████ (  4.7%)
       Germany ▏  711 ███ (  4.4%)
      Bulgaria ▏  576 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-07 ▏   55 ███████████████████████████████████ ( 20.4%)
2026-09-08 ▏   26 ████████████████ (  9.7%)
2026-09-09 ▏   39 ████████████████████████ ( 14.5%)
2026-09-10 ▏   31 ███████████████████ ( 11.5%)
2026-09-11 ▏   33 █████████████████████ ( 12.3%)
2026-09-12 ▏   51 ████████████████████████████████ ( 19.0%)
2026-09-13 ▏   32 ████████████████████ ( 11.9%)
2026-09-14 ▏    2 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!