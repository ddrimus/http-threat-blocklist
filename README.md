# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-441-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 441                      |
| Total Reports: 1,356                 |
| Unique Sources: 543                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  360 ███████████████████████████████████ ( 26.6%)
                HTTP Probing ▏  327 ███████████████████████████████ ( 24.2%)
HTTP Admin Interface Probing ▏  140 █████████████ ( 10.4%)
        HTTP Sensitive Files ▏  107 ██████████ (  7.9%)
         HTTP Wordpress Scan ▏   93 █████████ (  6.9%)
       CVE-2017-9841 Exploit ▏   84 ████████ (  6.2%)
      HTTP Crawl Non Statics ▏   64 ██████ (  4.7%)
     HTTP Backdoors Attempts ▏   57 █████ (  4.2%)
            HTTP CVE Probing ▏   45 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏   32 ███ (  2.4%)
      CVE-2022-41082 Exploit ▏   16 █ (  1.2%)
                 Netgear RCE ▏    9 █ (  0.7%)
 HTTP Path Traversal Probing ▏    9 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  384 ███████████████████████████████████ ( 31.7%)
United Kingdom ▏  287 ██████████████████████████ ( 23.7%)
       Ireland ▏  272 ████████████████████████ ( 22.4%)
   Netherlands ▏   52 ████ (  4.3%)
         Japan ▏   47 ████ (  3.9%)
     Singapore ▏   45 ████ (  3.7%)
      Bulgaria ▏   35 ███ (  2.9%)
       Germany ▏   32 ██ (  2.6%)
         China ▏   31 ██ (  2.6%)
         India ▏   28 ██ (  2.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-07 ▏   60 ██████████████████████ ( 11.9%)
2025-07-08 ▏   91 ██████████████████████████████████ ( 18.1%)
2025-07-09 ▏   65 ████████████████████████ ( 12.9%)
2025-07-10 ▏   59 ██████████████████████ ( 11.7%)
2025-07-11 ▏   72 ███████████████████████████ ( 14.3%)
2025-07-12 ▏   63 ███████████████████████ ( 12.5%)
2025-07-13 ▏   93 ███████████████████████████████████ ( 18.5%)
2025-07-14 ▏    1 █ (  0.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!