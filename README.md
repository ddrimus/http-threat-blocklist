# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-506-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 506                      |
| Total Reports: 5,671                 |
| Unique Sources: 1,644                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1497 ███████████████████████████████████ ( 26.6%)
         HTTP Bad User Agent ▏ 1249 █████████████████████████████ ( 22.2%)
HTTP Admin Interface Probing ▏  617 ██████████████ ( 11.0%)
        HTTP Sensitive Files ▏  514 ████████████ (  9.1%)
         HTTP Wordpress Scan ▏  436 ██████████ (  7.7%)
       CVE-2017-9841 Exploit ▏  298 ██████ (  5.3%)
      HTTP Crawl Non Statics ▏  283 ██████ (  5.0%)
     HTTP Backdoors Attempts ▏  257 ██████ (  4.6%)
            HTTP CVE Probing ▏  194 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  120 ██ (  2.1%)
      CVE-2022-41082 Exploit ▏   53 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
                 Netgear RCE ▏   38 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   19 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   17 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1602 ███████████████████████████████████ ( 33.0%)
United Kingdom ▏  837 ██████████████████ ( 17.3%)
       Ireland ▏  732 ███████████████ ( 15.1%)
        France ▏  369 ████████ (  7.6%)
     Singapore ▏  277 ██████ (  5.7%)
     Australia ▏  251 █████ (  5.2%)
         Japan ▏  239 █████ (  4.9%)
   Netherlands ▏  207 ████ (  4.3%)
       Germany ▏  183 ███ (  3.8%)
      Bulgaria ▏  155 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-19 ▏   48 █████████████████████████ ( 13.5%)
2025-09-20 ▏   50 ██████████████████████████ ( 14.0%)
2025-09-21 ▏   61 ████████████████████████████████ ( 17.1%)
2025-09-22 ▏   40 █████████████████████ ( 11.2%)
2025-09-23 ▏   66 ███████████████████████████████████ ( 18.5%)
2025-09-24 ▏   41 █████████████████████ ( 11.5%)
2025-09-25 ▏   46 ████████████████████████ ( 12.9%)
2025-09-26 ▏    4 ██ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!