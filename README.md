# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-517-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--03-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 517                      |
| Total Reports: 7,608                 |
| Unique Sources: 2,136                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2119 ███████████████████████████████████ ( 28.0%)
         HTTP Bad User Agent ▏ 1673 ███████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  834 █████████████ ( 11.0%)
        HTTP Sensitive Files ▏  799 █████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  509 ████████ (  6.7%)
       CVE-2017-9841 Exploit ▏  348 █████ (  4.6%)
      HTTP Crawl Non Statics ▏  335 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  316 █████ (  4.2%)
            HTTP CVE Probing ▏  272 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  127 ██ (  1.7%)
      CVE-2022-41082 Exploit ▏   78 █ (  1.0%)
                 Netgear RCE ▏   63 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   25 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2258 ███████████████████████████████████ ( 34.4%)
United Kingdom ▏ 1239 ███████████████████ ( 18.9%)
       Ireland ▏  824 ████████████ ( 12.6%)
   Netherlands ▏  453 ███████ (  6.9%)
        France ▏  436 ██████ (  6.6%)
         Japan ▏  327 █████ (  5.0%)
     Singapore ▏  320 ████ (  4.9%)
     Australia ▏  278 ████ (  4.2%)
       Germany ▏  227 ███ (  3.5%)
         India ▏  200 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-27 ▏   48 ███████████████████████████ ( 12.3%)
2025-10-28 ▏   61 ███████████████████████████████████ ( 15.6%)
2025-10-29 ▏   52 █████████████████████████████ ( 13.3%)
2025-10-30 ▏   54 ██████████████████████████████ ( 13.8%)
2025-10-31 ▏   60 ██████████████████████████████████ ( 15.3%)
2025-11-01 ▏   49 ████████████████████████████ ( 12.5%)
2025-11-02 ▏   60 ██████████████████████████████████ ( 15.3%)
2025-11-03 ▏    7 ████ (  1.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!