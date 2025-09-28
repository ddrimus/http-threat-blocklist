# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-516-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--28-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 516                      |
| Total Reports: 5,755                 |
| Unique Sources: 1,672                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1518 ███████████████████████████████████ ( 26.6%)
         HTTP Bad User Agent ▏ 1286 █████████████████████████████ ( 22.5%)
HTTP Admin Interface Probing ▏  620 ██████████████ ( 10.8%)
        HTTP Sensitive Files ▏  524 ████████████ (  9.2%)
         HTTP Wordpress Scan ▏  438 ██████████ (  7.7%)
       CVE-2017-9841 Exploit ▏  300 ██████ (  5.2%)
      HTTP Crawl Non Statics ▏  284 ██████ (  5.0%)
     HTTP Backdoors Attempts ▏  257 █████ (  4.5%)
            HTTP CVE Probing ▏  198 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  121 ██ (  2.1%)
      CVE-2022-41082 Exploit ▏   54 █ (  0.9%)
                 Netgear RCE ▏   39 █ (  0.7%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   20 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   17 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1620 ███████████████████████████████████ ( 33.0%)
United Kingdom ▏  857 ██████████████████ ( 17.4%)
       Ireland ▏  735 ███████████████ ( 15.0%)
        France ▏  372 ████████ (  7.6%)
     Singapore ▏  278 ██████ (  5.7%)
     Australia ▏  258 █████ (  5.2%)
         Japan ▏  240 █████ (  4.9%)
   Netherlands ▏  210 ████ (  4.3%)
       Germany ▏  188 ████ (  3.8%)
      Bulgaria ▏  158 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-21 ▏   52 ███████████████████████████ ( 15.6%)
2025-09-22 ▏   40 █████████████████████ ( 12.0%)
2025-09-23 ▏   66 ███████████████████████████████████ ( 19.8%)
2025-09-24 ▏   41 █████████████████████ ( 12.3%)
2025-09-25 ▏   46 ████████████████████████ ( 13.8%)
2025-09-26 ▏   48 █████████████████████████ ( 14.4%)
2025-09-27 ▏   40 █████████████████████ ( 12.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!