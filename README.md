# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-505-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 505                      |
| Total Reports: 5,117                 |
| Unique Sources: 1,509                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1343 ███████████████████████████████████ ( 26.3%)
         HTTP Bad User Agent ▏ 1125 █████████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  542 ██████████████ ( 10.6%)
        HTTP Sensitive Files ▏  465 ████████████ (  9.1%)
         HTTP Wordpress Scan ▏  410 ██████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  287 ███████ (  5.6%)
      HTTP Crawl Non Statics ▏  258 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  238 ██████ (  4.7%)
            HTTP CVE Probing ▏  175 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  116 ███ (  2.3%)
      CVE-2022-41082 Exploit ▏   46 █ (  0.9%)
                 Netgear RCE ▏   35 █ (  0.7%)
 HTTP Path Traversal Probing ▏   29 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   17 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   15 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1351 ███████████████████████████████████ ( 30.8%)
United Kingdom ▏  775 ████████████████████ ( 17.7%)
       Ireland ▏  676 █████████████████ ( 15.4%)
        France ▏  365 █████████ (  8.3%)
     Singapore ▏  261 ██████ (  5.9%)
     Australia ▏  250 ██████ (  5.7%)
         Japan ▏  239 ██████ (  5.4%)
       Germany ▏  165 ████ (  3.8%)
   Netherlands ▏  157 ████ (  3.6%)
      Bulgaria ▏  150 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-09 ▏   55 ███████████████████████████████████ ( 23.0%)
2025-09-10 ▏    8 █████ (  3.3%)
2025-09-11 ▏   26 ████████████████ ( 10.9%)
2025-09-12 ▏   38 ████████████████████████ ( 15.9%)
2025-09-13 ▏   34 █████████████████████ ( 14.2%)
2025-09-14 ▏   36 ██████████████████████ ( 15.1%)
2025-09-15 ▏   37 ███████████████████████ ( 15.5%)
2025-09-16 ▏    5 ███ (  2.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!