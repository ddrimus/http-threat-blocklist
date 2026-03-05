# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-376-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--05-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 376                      |
| Total Reports: 12,404                |
| Unique Sources: 3,329                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3653 ███████████████████████████████████ ( 29.6%)
         HTTP Bad User Agent ▏ 2567 ████████████████████████ ( 20.8%)
HTTP Admin Interface Probing ▏ 1470 ██████████████ ( 11.9%)
        HTTP Sensitive Files ▏ 1255 ████████████ ( 10.2%)
         HTTP Wordpress Scan ▏  962 █████████ (  7.8%)
      HTTP Crawl Non Statics ▏  552 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  524 █████ (  4.2%)
            HTTP CVE Probing ▏  433 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  429 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.2%)
      CVE-2022-41082 Exploit ▏  130 █ (  1.1%)
                 Netgear RCE ▏  102 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   51 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   44 █ (  0.4%)
 HTTP Path Traversal Probing ▏   42 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3807 ███████████████████████████████████ ( 36.5%)
United Kingdom ▏ 1754 ████████████████ ( 16.8%)
       Ireland ▏ 1127 ██████████ ( 10.8%)
   Netherlands ▏  767 ███████ (  7.3%)
     Singapore ▏  616 █████ (  5.9%)
         Japan ▏  613 █████ (  5.9%)
        France ▏  594 █████ (  5.7%)
       Germany ▏  405 ███ (  3.9%)
     Australia ▏  400 ███ (  3.8%)
         India ▏  360 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-02-26 ▏   27 ███████████████ (  9.6%)
2026-02-27 ▏   37 ████████████████████ ( 13.2%)
2026-02-28 ▏   28 ███████████████ ( 10.0%)
2026-03-01 ▏   63 ███████████████████████████████████ ( 22.4%)
2026-03-02 ▏   46 █████████████████████████ ( 16.4%)
2026-03-03 ▏   48 ██████████████████████████ ( 17.1%)
2026-03-04 ▏   29 ████████████████ ( 10.3%)
2026-03-05 ▏    3 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!