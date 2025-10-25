# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-526-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 526                      |
| Total Reports: 7,088                 |
| Unique Sources: 2,035                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1951 ███████████████████████████████████ ( 27.7%)
         HTTP Bad User Agent ▏ 1557 ███████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  767 █████████████ ( 10.9%)
        HTTP Sensitive Files ▏  719 ████████████ ( 10.2%)
         HTTP Wordpress Scan ▏  486 ████████ (  6.9%)
       CVE-2017-9841 Exploit ▏  342 ██████ (  4.9%)
      HTTP Crawl Non Statics ▏  320 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  297 █████ (  4.2%)
            HTTP CVE Probing ▏  258 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.8%)
      CVE-2022-41082 Exploit ▏   74 █ (  1.1%)
                 Netgear RCE ▏   59 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   25 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2099 ███████████████████████████████████ ( 34.5%)
United Kingdom ▏ 1124 ██████████████████ ( 18.5%)
       Ireland ▏  792 █████████████ ( 13.0%)
        France ▏  410 ██████ (  6.7%)
   Netherlands ▏  383 ██████ (  6.3%)
     Singapore ▏  315 █████ (  5.2%)
         Japan ▏  301 █████ (  4.9%)
     Australia ▏  270 ████ (  4.4%)
       Germany ▏  217 ███ (  3.6%)
         India ▏  181 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-18 ▏   45 ███████████████████ (  9.5%)
2025-10-19 ▏   69 ██████████████████████████████ ( 14.6%)
2025-10-20 ▏   54 ███████████████████████ ( 11.4%)
2025-10-21 ▏   76 █████████████████████████████████ ( 16.0%)
2025-10-22 ▏   73 ███████████████████████████████ ( 15.4%)
2025-10-23 ▏   80 ███████████████████████████████████ ( 16.9%)
2025-10-24 ▏   76 █████████████████████████████████ ( 16.0%)
2025-10-25 ▏    1 █ (  0.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!