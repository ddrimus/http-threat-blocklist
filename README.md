# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-503-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 503                      |
| Total Reports: 5,624                 |
| Unique Sources: 1,631                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1485 ███████████████████████████████████ ( 26.6%)
         HTTP Bad User Agent ▏ 1234 █████████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  613 ██████████████ ( 11.0%)
        HTTP Sensitive Files ▏  512 ████████████ (  9.2%)
         HTTP Wordpress Scan ▏  436 ██████████ (  7.8%)
       CVE-2017-9841 Exploit ▏  293 ██████ (  5.2%)
      HTTP Crawl Non Statics ▏  282 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  256 ██████ (  4.6%)
            HTTP CVE Probing ▏  192 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  117 ██ (  2.1%)
      CVE-2022-41082 Exploit ▏   52 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
                 Netgear RCE ▏   38 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   18 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   17 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1589 ███████████████████████████████████ ( 32.9%)
United Kingdom ▏  837 ██████████████████ ( 17.4%)
       Ireland ▏  730 ████████████████ ( 15.1%)
        France ▏  369 ████████ (  7.7%)
     Singapore ▏  271 █████ (  5.6%)
     Australia ▏  251 █████ (  5.2%)
         Japan ▏  239 █████ (  5.0%)
   Netherlands ▏  199 ████ (  4.1%)
       Germany ▏  183 ████ (  3.8%)
      Bulgaria ▏  155 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-18 ▏   72 ███████████████████████████████████ ( 18.6%)
2025-09-19 ▏   54 ██████████████████████████ ( 14.0%)
2025-09-20 ▏   50 ████████████████████████ ( 12.9%)
2025-09-21 ▏   61 █████████████████████████████ ( 15.8%)
2025-09-22 ▏   40 ███████████████████ ( 10.3%)
2025-09-23 ▏   66 ████████████████████████████████ ( 17.1%)
2025-09-24 ▏   41 ███████████████████ ( 10.6%)
2025-09-25 ▏    3 █ (  0.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!