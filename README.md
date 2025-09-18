# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-498-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 498                      |
| Total Reports: 5,237                 |
| Unique Sources: 1,535                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1374 ███████████████████████████████████ ( 26.4%)
         HTTP Bad User Agent ▏ 1148 █████████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  556 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  474 ████████████ (  9.1%)
         HTTP Wordpress Scan ▏  415 ██████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  290 ███████ (  5.6%)
      HTTP Crawl Non Statics ▏  265 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  242 ██████ (  4.6%)
            HTTP CVE Probing ▏  179 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  116 ██ (  2.2%)
      CVE-2022-41082 Exploit ▏   48 █ (  0.9%)
                 Netgear RCE ▏   36 █ (  0.7%)
 HTTP Path Traversal Probing ▏   34 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   17 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   15 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1418 ███████████████████████████████████ ( 31.6%)
United Kingdom ▏  783 ███████████████████ ( 17.4%)
       Ireland ▏  689 █████████████████ ( 15.3%)
        France ▏  367 █████████ (  8.2%)
     Singapore ▏  265 ██████ (  5.9%)
     Australia ▏  250 ██████ (  5.6%)
         Japan ▏  239 █████ (  5.3%)
       Germany ▏  171 ████ (  3.8%)
   Netherlands ▏  160 ███ (  3.6%)
      Bulgaria ▏  150 ███ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-11 ▏   26 ████████████ (  8.8%)
2025-09-12 ▏   38 ██████████████████ ( 12.8%)
2025-09-13 ▏   34 ████████████████ ( 11.5%)
2025-09-14 ▏   36 █████████████████ ( 12.2%)
2025-09-15 ▏   37 █████████████████ ( 12.5%)
2025-09-16 ▏   73 ███████████████████████████████████ ( 24.7%)
2025-09-17 ▏   51 ████████████████████████ ( 17.2%)
2025-09-18 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!