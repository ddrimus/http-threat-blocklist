# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-336-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--03-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 336                      |
| Total Reports: 11,273                |
| Unique Sources: 3,071                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3304 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2448 █████████████████████████ ( 21.8%)
HTTP Admin Interface Probing ▏ 1279 █████████████ ( 11.4%)
        HTTP Sensitive Files ▏ 1220 ████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  758 ████████ (  6.8%)
      HTTP Crawl Non Statics ▏  474 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  452 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  416 ████ (  3.7%)
            HTTP CVE Probing ▏  391 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  142 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  116 █ (  1.0%)
                 Netgear RCE ▏   93 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.5%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   40 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3465 ███████████████████████████████████ ( 35.8%)
United Kingdom ▏ 1739 █████████████████ ( 18.0%)
       Ireland ▏ 1032 ██████████ ( 10.7%)
   Netherlands ▏  730 ███████ (  7.5%)
         Japan ▏  558 █████ (  5.8%)
     Singapore ▏  538 █████ (  5.6%)
        France ▏  535 █████ (  5.5%)
       Germany ▏  385 ███ (  4.0%)
     Australia ▏  363 ███ (  3.8%)
         India ▏  333 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-27 ▏   28 ██████████████████████████ ( 14.4%)
2026-01-28 ▏   23 █████████████████████ ( 11.9%)
2026-01-29 ▏   31 █████████████████████████████ ( 16.0%)
2026-01-30 ▏   33 ███████████████████████████████ ( 17.0%)
2026-01-31 ▏   37 ███████████████████████████████████ ( 19.1%)
2026-02-01 ▏   17 ████████████████ (  8.8%)
2026-02-02 ▏   23 █████████████████████ ( 11.9%)
2026-02-03 ▏    2 █ (  1.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!