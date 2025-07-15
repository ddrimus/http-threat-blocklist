# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-438-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--15-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 438                      |
| Total Reports: 1,418                 |
| Unique Sources: 560                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  376 ███████████████████████████████████ ( 26.6%)
                HTTP Probing ▏  341 ███████████████████████████████ ( 24.1%)
HTTP Admin Interface Probing ▏  146 █████████████ ( 10.3%)
        HTTP Sensitive Files ▏  114 ██████████ (  8.1%)
         HTTP Wordpress Scan ▏   98 █████████ (  6.9%)
       CVE-2017-9841 Exploit ▏   88 ████████ (  6.2%)
      HTTP Crawl Non Statics ▏   67 ██████ (  4.7%)
     HTTP Backdoors Attempts ▏   60 █████ (  4.2%)
            HTTP CVE Probing ▏   46 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏   34 ███ (  2.4%)
      CVE-2022-41082 Exploit ▏   17 █ (  1.2%)
                 Netgear RCE ▏    9 █ (  0.6%)
 HTTP Path Traversal Probing ▏    9 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  401 ███████████████████████████████████ ( 31.7%)
United Kingdom ▏  301 ██████████████████████████ ( 23.8%)
       Ireland ▏  282 ████████████████████████ ( 22.3%)
         Japan ▏   54 ████ (  4.3%)
   Netherlands ▏   53 ████ (  4.2%)
     Singapore ▏   49 ████ (  3.9%)
      Bulgaria ▏   35 ███ (  2.8%)
       Germany ▏   32 ██ (  2.5%)
         China ▏   31 ██ (  2.4%)
         India ▏   28 ██ (  2.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-08 ▏   74 ███████████████████████████ ( 15.1%)
2025-07-09 ▏   65 ████████████████████████ ( 13.3%)
2025-07-10 ▏   59 ██████████████████████ ( 12.1%)
2025-07-11 ▏   72 ███████████████████████████ ( 14.7%)
2025-07-12 ▏   63 ███████████████████████ ( 12.9%)
2025-07-13 ▏   93 ███████████████████████████████████ ( 19.0%)
2025-07-14 ▏   53 ███████████████████ ( 10.8%)
2025-07-15 ▏   10 ███ (  2.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!