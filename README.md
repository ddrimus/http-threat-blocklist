# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-433-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--13-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 433                      |
| Total Reports: 1,275                 |
| Unique Sources: 519                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  347 ███████████████████████████████████ ( 27.3%)
                HTTP Probing ▏  312 ███████████████████████████████ ( 24.5%)
HTTP Admin Interface Probing ▏  128 ████████████ ( 10.1%)
        HTTP Sensitive Files ▏  104 ██████████ (  8.2%)
         HTTP Wordpress Scan ▏   83 ████████ (  6.5%)
       CVE-2017-9841 Exploit ▏   75 ███████ (  5.9%)
      HTTP Crawl Non Statics ▏   58 █████ (  4.6%)
     HTTP Backdoors Attempts ▏   49 ████ (  3.9%)
            HTTP CVE Probing ▏   43 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏   29 ██ (  2.3%)
      CVE-2022-41082 Exploit ▏   16 █ (  1.3%)
                 Netgear RCE ▏    9 █ (  0.7%)
 HTTP Path Traversal Probing ▏    9 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  372 ███████████████████████████████████ ( 32.3%)
United Kingdom ▏  276 █████████████████████████ ( 24.0%)
       Ireland ▏  248 ███████████████████████ ( 21.6%)
   Netherlands ▏   52 ████ (  4.5%)
     Singapore ▏   44 ████ (  3.8%)
         Japan ▏   35 ███ (  3.0%)
       Germany ▏   32 ███ (  2.8%)
      Bulgaria ▏   32 ███ (  2.8%)
         China ▏   31 ██ (  2.7%)
         India ▏   28 ██ (  2.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-06 ▏   40 ███████████████ (  8.6%)
2025-07-07 ▏   64 ████████████████████████ ( 13.7%)
2025-07-08 ▏   91 ███████████████████████████████████ ( 19.5%)
2025-07-09 ▏   65 █████████████████████████ ( 13.9%)
2025-07-10 ▏   59 ██████████████████████ ( 12.6%)
2025-07-11 ▏   72 ███████████████████████████ ( 15.4%)
2025-07-12 ▏   63 ████████████████████████ ( 13.5%)
2025-07-13 ▏   13 █████ (  2.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!