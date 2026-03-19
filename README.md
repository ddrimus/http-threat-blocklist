# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-371-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 371                      |
| Total Reports: 12,915                |
| Unique Sources: 3,424                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3813 ███████████████████████████████████ ( 29.7%)
         HTTP Bad User Agent ▏ 2618 ████████████████████████ ( 20.4%)
HTTP Admin Interface Probing ▏ 1564 ██████████████ ( 12.2%)
        HTTP Sensitive Files ▏ 1271 ███████████ (  9.9%)
         HTTP Wordpress Scan ▏ 1051 █████████ (  8.2%)
      HTTP Crawl Non Statics ▏  580 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  534 ████ (  4.2%)
            HTTP CVE Probing ▏  454 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  438 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  143 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  136 █ (  1.1%)
                 Netgear RCE ▏  104 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   53 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3952 ███████████████████████████████████ ( 36.5%)
United Kingdom ▏ 1755 ███████████████ ( 16.2%)
       Ireland ▏ 1142 ██████████ ( 10.5%)
   Netherlands ▏  800 ███████ (  7.4%)
     Singapore ▏  661 █████ (  6.1%)
         Japan ▏  652 █████ (  6.0%)
        France ▏  625 █████ (  5.8%)
       Germany ▏  469 ████ (  4.3%)
     Australia ▏  409 ███ (  3.8%)
         India ▏  371 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-12 ▏   36 ██████████████ ( 11.7%)
2026-03-13 ▏   45 █████████████████ ( 14.6%)
2026-03-14 ▏   38 ███████████████ ( 12.3%)
2026-03-15 ▏   88 ███████████████████████████████████ ( 28.5%)
2026-03-16 ▏   27 ██████████ (  8.7%)
2026-03-17 ▏   22 ████████ (  7.1%)
2026-03-18 ▏   52 ████████████████████ ( 16.8%)
2026-03-19 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!