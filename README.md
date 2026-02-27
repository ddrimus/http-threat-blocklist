# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-362-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 362                      |
| Total Reports: 12,152                |
| Unique Sources: 3,276                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3573 ███████████████████████████████████ ( 29.5%)
         HTTP Bad User Agent ▏ 2545 ████████████████████████ ( 21.0%)
HTTP Admin Interface Probing ▏ 1416 █████████████ ( 11.7%)
        HTTP Sensitive Files ▏ 1250 ████████████ ( 10.3%)
         HTTP Wordpress Scan ▏  911 ████████ (  7.5%)
      HTTP Crawl Non Statics ▏  537 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  508 ████ (  4.2%)
            HTTP CVE Probing ▏  428 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  428 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  128 █ (  1.1%)
                 Netgear RCE ▏  101 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   44 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3732 ███████████████████████████████████ ( 36.2%)
United Kingdom ▏ 1753 ████████████████ ( 17.0%)
       Ireland ▏ 1126 ██████████ ( 10.9%)
   Netherlands ▏  758 ███████ (  7.3%)
     Singapore ▏  612 █████ (  5.9%)
         Japan ▏  593 █████ (  5.7%)
        France ▏  590 █████ (  5.7%)
       Germany ▏  401 ███ (  3.9%)
     Australia ▏  393 ███ (  3.8%)
         India ▏  360 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-20 ▏   17 █████████ (  6.5%)
2026-02-21 ▏   40 ███████████████████████ ( 15.3%)
2026-02-22 ▏   46 ██████████████████████████ ( 17.6%)
2026-02-23 ▏   60 ███████████████████████████████████ ( 22.9%)
2026-02-24 ▏   41 ███████████████████████ ( 15.6%)
2026-02-25 ▏   26 ███████████████ (  9.9%)
2026-02-26 ▏   30 █████████████████ ( 11.5%)
2026-02-27 ▏    2 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!