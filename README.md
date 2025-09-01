# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-575-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--01-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 575                      |
| Total Reports: 4,485                 |
| Unique Sources: 1,337                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1134 ███████████████████████████████████ ( 25.4%)
         HTTP Bad User Agent ▏ 1014 ███████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  483 ██████████████ ( 10.8%)
        HTTP Sensitive Files ▏  385 ███████████ (  8.6%)
         HTTP Wordpress Scan ▏  365 ███████████ (  8.2%)
       CVE-2017-9841 Exploit ▏  268 ████████ (  6.0%)
      HTTP Crawl Non Statics ▏  220 ██████ (  4.9%)
     HTTP Backdoors Attempts ▏  216 ██████ (  4.8%)
            HTTP CVE Probing ▏  150 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  111 ███ (  2.5%)
      CVE-2022-41082 Exploit ▏   37 █ (  0.8%)
                 Netgear RCE ▏   30 █ (  0.7%)
 HTTP Path Traversal Probing ▏   29 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   14 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1199 ███████████████████████████████████ ( 31.0%)
United Kingdom ▏  665 ███████████████████ ( 17.2%)
       Ireland ▏  587 █████████████████ ( 15.2%)
        France ▏  301 ████████ (  7.8%)
     Australia ▏  249 ███████ (  6.4%)
         Japan ▏  237 ██████ (  6.1%)
     Singapore ▏  218 ██████ (  5.6%)
       Germany ▏  144 ████ (  3.7%)
      Bulgaria ▏  136 ███ (  3.5%)
   Netherlands ▏  135 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-25 ▏   58 ██████████████████████ ( 14.2%)
2025-08-26 ▏   92 ███████████████████████████████████ ( 22.5%)
2025-08-27 ▏   50 ███████████████████ ( 12.3%)
2025-08-28 ▏   45 █████████████████ ( 11.0%)
2025-08-29 ▏   59 ██████████████████████ ( 14.5%)
2025-08-30 ▏   55 ████████████████████ ( 13.5%)
2025-08-31 ▏   48 ██████████████████ ( 11.8%)
2025-09-01 ▏    1 █ (  0.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!