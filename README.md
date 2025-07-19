# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-472-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 472                      |
| Total Reports: 1,801                 |
| Unique Sources: 654                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  442 ███████████████████████████████████ ( 24.7%)
                HTTP Probing ▏  439 ██████████████████████████████████ ( 24.5%)
HTTP Admin Interface Probing ▏  191 ███████████████ ( 10.7%)
        HTTP Sensitive Files ▏  144 ███████████ (  8.0%)
         HTTP Wordpress Scan ▏  136 ██████████ (  7.6%)
       CVE-2017-9841 Exploit ▏  108 ████████ (  6.0%)
     HTTP Backdoors Attempts ▏   93 ███████ (  5.2%)
      HTTP Crawl Non Statics ▏   85 ██████ (  4.7%)
            HTTP CVE Probing ▏   55 ████ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏   49 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏   20 █ (  1.1%)
                 Netgear RCE ▏   11 █ (  0.6%)
 HTTP Path Traversal Probing ▏    9 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  482 ███████████████████████████████████ ( 30.0%)
United Kingdom ▏  380 ███████████████████████████ ( 23.6%)
       Ireland ▏  355 █████████████████████████ ( 22.1%)
         Japan ▏   76 █████ (  4.7%)
   Netherlands ▏   75 █████ (  4.7%)
     Singapore ▏   60 ████ (  3.7%)
     Australia ▏   57 ████ (  3.5%)
       Germany ▏   45 ███ (  2.8%)
         China ▏   42 ███ (  2.6%)
      Bulgaria ▏   35 ██ (  2.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-12 ▏   50 ████████████████ (  8.5%)
2025-07-13 ▏   93 ███████████████████████████████ ( 15.8%)
2025-07-14 ▏   53 █████████████████ (  9.0%)
2025-07-15 ▏  104 ██████████████████████████████████ ( 17.7%)
2025-07-16 ▏   88 █████████████████████████████ ( 14.9%)
2025-07-17 ▏   88 █████████████████████████████ ( 14.9%)
2025-07-18 ▏  105 ███████████████████████████████████ ( 17.8%)
2025-07-19 ▏    8 ██ (  1.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!