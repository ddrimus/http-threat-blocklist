# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-539-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--31-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 539                      |
| Total Reports: 2,614                 |
| Unique Sources: 878                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  648 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  613 █████████████████████████████████ ( 23.5%)
HTTP Admin Interface Probing ▏  278 ███████████████ ( 10.7%)
        HTTP Sensitive Files ▏  212 ███████████ (  8.1%)
         HTTP Wordpress Scan ▏  197 ██████████ (  7.6%)
       CVE-2017-9841 Exploit ▏  174 █████████ (  6.7%)
     HTTP Backdoors Attempts ▏  134 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  119 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏   82 ████ (  3.1%)
            HTTP CVE Probing ▏   79 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   25 █ (  1.0%)
                 Netgear RCE ▏   15 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
 HTTP Path Traversal Probing ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    6 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  721 ███████████████████████████████████ ( 31.1%)
United Kingdom ▏  505 ████████████████████████ ( 21.8%)
       Ireland ▏  433 █████████████████████ ( 18.7%)
         Japan ▏  147 ███████ (  6.3%)
     Australia ▏  133 ██████ (  5.7%)
   Netherlands ▏  102 ████ (  4.4%)
     Singapore ▏   96 ████ (  4.1%)
       Germany ▏   73 ███ (  3.1%)
         China ▏   63 ███ (  2.7%)
      Bulgaria ▏   47 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-24 ▏   59 ███████████████████████████ ( 14.9%)
2025-07-25 ▏   76 ███████████████████████████████████ ( 19.1%)
2025-07-26 ▏   69 ███████████████████████████████ ( 17.4%)
2025-07-27 ▏   61 ████████████████████████████ ( 15.4%)
2025-07-28 ▏   65 █████████████████████████████ ( 16.4%)
2025-07-29 ▏   48 ██████████████████████ ( 12.1%)
2025-07-30 ▏   12 █████ (  3.0%)
2025-07-31 ▏    7 ███ (  1.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!