# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-567-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--13-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 567                      |
| Total Reports: 8,249                 |
| Unique Sources: 2,293                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2343 ███████████████████████████████████ ( 28.6%)
         HTTP Bad User Agent ▏ 1810 ███████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  889 █████████████ ( 10.8%)
        HTTP Sensitive Files ▏  882 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  549 ████████ (  6.7%)
      HTTP Crawl Non Statics ▏  358 █████ (  4.4%)
       CVE-2017-9841 Exploit ▏  357 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  347 █████ (  4.2%)
            HTTP CVE Probing ▏  293 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  128 █ (  1.6%)
      CVE-2022-41082 Exploit ▏   83 █ (  1.0%)
                 Netgear RCE ▏   67 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   29 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   28 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2434 ███████████████████████████████████ ( 34.2%)
United Kingdom ▏ 1356 ███████████████████ ( 19.1%)
       Ireland ▏  871 ████████████ ( 12.2%)
   Netherlands ▏  518 ███████ (  7.3%)
        France ▏  443 ██████ (  6.2%)
         Japan ▏  410 █████ (  5.8%)
     Singapore ▏  328 ████ (  4.6%)
     Australia ▏  278 ███ (  3.9%)
       Germany ▏  253 ███ (  3.6%)
         India ▏  220 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-06 ▏   42 ████████████████ (  9.2%)
2025-11-07 ▏   68 ██████████████████████████ ( 14.9%)
2025-11-08 ▏   89 ███████████████████████████████████ ( 19.5%)
2025-11-09 ▏   65 █████████████████████████ ( 14.2%)
2025-11-10 ▏   63 ████████████████████████ ( 13.8%)
2025-11-11 ▏   57 ██████████████████████ ( 12.5%)
2025-11-12 ▏   73 ████████████████████████████ ( 16.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!