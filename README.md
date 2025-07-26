# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-513-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 513                      |
| Total Reports: 2,360                 |
| Unique Sources: 798                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  580 ███████████████████████████████████ ( 24.7%)
         HTTP Bad User Agent ▏  552 █████████████████████████████████ ( 23.5%)
HTTP Admin Interface Probing ▏  254 ███████████████ ( 10.8%)
        HTTP Sensitive Files ▏  198 ███████████ (  8.4%)
         HTTP Wordpress Scan ▏  177 ██████████ (  7.5%)
       CVE-2017-9841 Exploit ▏  155 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  121 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  113 ██████ (  4.8%)
   CVE-2018-20062 (Thinkphp) ▏   73 ████ (  3.1%)
            HTTP CVE Probing ▏   69 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   24 █ (  1.0%)
                 Netgear RCE ▏   13 █ (  0.6%)
 HTTP Path Traversal Probing ▏   11 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  637 ███████████████████████████████████ ( 30.4%)
United Kingdom ▏  486 ██████████████████████████ ( 23.2%)
       Ireland ▏  415 ██████████████████████ ( 19.8%)
     Australia ▏  113 ██████ (  5.4%)
         Japan ▏  109 █████ (  5.2%)
   Netherlands ▏   98 █████ (  4.7%)
     Singapore ▏   83 ████ (  4.0%)
       Germany ▏   57 ███ (  2.7%)
         China ▏   55 ███ (  2.6%)
      Bulgaria ▏   41 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-19 ▏   77 ████████████████████████████ ( 13.8%)
2025-07-20 ▏   66 ████████████████████████ ( 11.8%)
2025-07-21 ▏   93 ██████████████████████████████████ ( 16.6%)
2025-07-22 ▏   95 ███████████████████████████████████ ( 17.0%)
2025-07-23 ▏   84 ██████████████████████████████ ( 15.0%)
2025-07-24 ▏   60 ██████████████████████ ( 10.7%)
2025-07-25 ▏   76 ████████████████████████████ ( 13.6%)
2025-07-26 ▏    8 ██ (  1.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!