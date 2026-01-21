# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-379-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--01--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 379                      |
| Total Reports: 10,859                |
| Unique Sources: 2,973                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3182 ███████████████████████████████████ ( 29.4%)
         HTTP Bad User Agent ▏ 2394 ██████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏ 1209 █████████████ ( 11.2%)
        HTTP Sensitive Files ▏ 1191 █████████████ ( 11.0%)
         HTTP Wordpress Scan ▏  699 ███████ (  6.5%)
      HTTP Crawl Non Statics ▏  461 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  423 ████ (  3.9%)
       CVE-2017-9841 Exploit ▏  410 ████ (  3.8%)
            HTTP CVE Probing ▏  370 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  142 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  110 █ (  1.0%)
                 Netgear RCE ▏   90 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   49 █ (  0.5%)
 HTTP Path Traversal Probing ▏   42 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   40 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3375 ███████████████████████████████████ ( 36.2%)
United Kingdom ▏ 1693 █████████████████ ( 18.1%)
       Ireland ▏ 1001 ██████████ ( 10.7%)
   Netherlands ▏  718 ███████ (  7.7%)
        France ▏  517 █████ (  5.5%)
         Japan ▏  506 █████ (  5.4%)
     Singapore ▏  500 █████ (  5.4%)
       Germany ▏  378 ███ (  4.1%)
     Australia ▏  342 ███ (  3.7%)
         India ▏  300 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-14 ▏   22 ████████████ ( 17.7%)
2026-01-15 ▏   60 ███████████████████████████████████ ( 48.4%)
2026-01-16 ▏   30 █████████████████ ( 24.2%)
2026-01-17 ▏   12 ███████ (  9.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!