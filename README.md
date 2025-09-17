# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-498-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--17-brightgreen)](.)

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
| Total Reports: 5,197                 |
| Unique Sources: 1,518                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1359 ███████████████████████████████████ ( 26.3%)
         HTTP Bad User Agent ▏ 1135 █████████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  554 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  470 ████████████ (  9.1%)
         HTTP Wordpress Scan ▏  413 ██████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  289 ███████ (  5.6%)
      HTTP Crawl Non Statics ▏  264 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  241 ██████ (  4.7%)
            HTTP CVE Probing ▏  178 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  116 ██ (  2.2%)
      CVE-2022-41082 Exploit ▏   48 █ (  0.9%)
                 Netgear RCE ▏   36 █ (  0.7%)
 HTTP Path Traversal Probing ▏   34 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   17 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   15 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1402 ███████████████████████████████████ ( 31.5%)
United Kingdom ▏  779 ███████████████████ ( 17.5%)
       Ireland ▏  684 █████████████████ ( 15.3%)
        France ▏  366 █████████ (  8.2%)
     Singapore ▏  263 ██████ (  5.9%)
     Australia ▏  250 ██████ (  5.6%)
         Japan ▏  239 █████ (  5.4%)
       Germany ▏  166 ████ (  3.7%)
   Netherlands ▏  158 ███ (  3.5%)
      Bulgaria ▏  150 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-10 ▏    8 ███ (  3.0%)
2025-09-11 ▏   26 ████████████ (  9.8%)
2025-09-12 ▏   38 ██████████████████ ( 14.4%)
2025-09-13 ▏   34 ████████████████ ( 12.9%)
2025-09-14 ▏   36 █████████████████ ( 13.6%)
2025-09-15 ▏   37 █████████████████ ( 14.0%)
2025-09-16 ▏   73 ███████████████████████████████████ ( 27.7%)
2025-09-17 ▏   12 █████ (  4.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!