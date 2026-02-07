# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-331-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--02--07-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 331                      |
| Total Reports: 11,420                |
| Unique Sources: 3,104                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3341 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2469 █████████████████████████ ( 21.7%)
HTTP Admin Interface Probing ▏ 1303 █████████████ ( 11.5%)
        HTTP Sensitive Files ▏ 1223 ████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  789 ████████ (  6.9%)
      HTTP Crawl Non Statics ▏  481 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  461 ████ (  4.1%)
       CVE-2017-9841 Exploit ▏  421 ████ (  3.7%)
            HTTP CVE Probing ▏  399 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  142 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  118 █ (  1.0%)
                 Netgear RCE ▏   93 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   40 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3519 ███████████████████████████████████ ( 35.9%)
United Kingdom ▏ 1743 █████████████████ ( 17.8%)
       Ireland ▏ 1050 ██████████ ( 10.7%)
   Netherlands ▏  730 ███████ (  7.4%)
         Japan ▏  570 █████ (  5.8%)
     Singapore ▏  563 █████ (  5.7%)
        France ▏  535 █████ (  5.5%)
       Germany ▏  388 ███ (  4.0%)
     Australia ▏  374 ███ (  3.8%)
         India ▏  334 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-31 ▏   32 ██████████████████████████ ( 14.5%)
2026-02-01 ▏   17 █████████████ (  7.7%)
2026-02-02 ▏   23 ██████████████████ ( 10.4%)
2026-02-03 ▏   43 ███████████████████████████████████ ( 19.5%)
2026-02-04 ▏   28 ██████████████████████ ( 12.7%)
2026-02-05 ▏   42 ██████████████████████████████████ ( 19.0%)
2026-02-06 ▏   35 ████████████████████████████ ( 15.8%)
2026-02-07 ▏    1 █ (  0.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!