# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-498-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--28-brightgreen)](.)

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
| Total Reports: 14,920                |
| Unique Sources: 3,998                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4431 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2843 ██████████████████████ ( 19.1%)
HTTP Admin Interface Probing ▏ 1883 ██████████████ ( 12.7%)
        HTTP Sensitive Files ▏ 1408 ███████████ (  9.5%)
         HTTP Wordpress Scan ▏ 1311 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  796 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  630 ████ (  4.2%)
            HTTP CVE Probing ▏  526 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  443 ███ (  3.0%)
      CVE-2022-41082 Exploit ▏  162 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.0%)
                 Netgear RCE ▏  115 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   50 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   48 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4553 ███████████████████████████████████ ( 37.1%)
United Kingdom ▏ 1770 █████████████ ( 14.4%)
       Ireland ▏ 1255 █████████ ( 10.2%)
   Netherlands ▏  880 ██████ (  7.2%)
        France ▏  813 ██████ (  6.6%)
     Singapore ▏  707 █████ (  5.8%)
         Japan ▏  693 █████ (  5.7%)
        Canada ▏  566 ████ (  4.6%)
       Germany ▏  528 ████ (  4.3%)
     Australia ▏  499 ███ (  4.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-21 ▏   39 ████████████████████ ( 10.7%)
2026-04-22 ▏   55 ████████████████████████████ ( 15.0%)
2026-04-23 ▏   54 ███████████████████████████ ( 14.8%)
2026-04-24 ▏   39 ████████████████████ ( 10.7%)
2026-04-25 ▏   53 ███████████████████████████ ( 14.5%)
2026-04-26 ▏   57 █████████████████████████████ ( 15.6%)
2026-04-27 ▏   68 ███████████████████████████████████ ( 18.6%)
2026-04-28 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!