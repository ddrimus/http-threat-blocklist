# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-423-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--10-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 423                      |
| Total Reports: 1,074                 |
| Unique Sources: 456                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  293 ███████████████████████████████████ ( 27.4%)
                HTTP Probing ▏  268 ████████████████████████████████ ( 25.0%)
HTTP Admin Interface Probing ▏  110 █████████████ ( 10.3%)
        HTTP Sensitive Files ▏   83 █████████ (  7.8%)
         HTTP Wordpress Scan ▏   67 ████████ (  6.3%)
       CVE-2017-9841 Exploit ▏   63 ███████ (  5.9%)
      HTTP Crawl Non Statics ▏   50 █████ (  4.7%)
            HTTP CVE Probing ▏   36 ████ (  3.4%)
     HTTP Backdoors Attempts ▏   35 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏   27 ███ (  2.5%)
      CVE-2022-41082 Exploit ▏   14 █ (  1.3%)
 HTTP Path Traversal Probing ▏    9 █ (  0.8%)
                 Netgear RCE ▏    6 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.5%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  328 ███████████████████████████████████ ( 33.9%)
United Kingdom ▏  237 █████████████████████████ ( 24.5%)
       Ireland ▏  200 █████████████████████ ( 20.7%)
   Netherlands ▏   43 ████ (  4.4%)
     Singapore ▏   41 ████ (  4.2%)
         Japan ▏   27 ██ (  2.8%)
       Germany ▏   26 ██ (  2.7%)
         China ▏   26 ██ (  2.7%)
      Bulgaria ▏   23 ██ (  2.4%)
          Iran ▏   17 █ (  1.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-03 ▏   72 ███████████████████████████ ( 16.2%)
2025-07-04 ▏   39 ███████████████ (  8.8%)
2025-07-05 ▏   62 ███████████████████████ ( 14.0%)
2025-07-06 ▏   45 █████████████████ ( 10.1%)
2025-07-07 ▏   64 ████████████████████████ ( 14.4%)
2025-07-08 ▏   91 ███████████████████████████████████ ( 20.5%)
2025-07-09 ▏   65 █████████████████████████ ( 14.6%)
2025-07-10 ▏    6 ██ (  1.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!