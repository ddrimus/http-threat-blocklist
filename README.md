# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-532-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--22-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 532                      |
| Total Reports: 8,675                 |
| Unique Sources: 2,393                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2471 ███████████████████████████████████ ( 28.6%)
         HTTP Bad User Agent ▏ 1922 ███████████████████████████ ( 22.3%)
        HTTP Sensitive Files ▏  941 █████████████ ( 10.9%)
HTTP Admin Interface Probing ▏  927 █████████████ ( 10.7%)
         HTTP Wordpress Scan ▏  562 ███████ (  6.5%)
       CVE-2017-9841 Exploit ▏  373 █████ (  4.3%)
      HTTP Crawl Non Statics ▏  366 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  354 █████ (  4.1%)
            HTTP CVE Probing ▏  314 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  131 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   89 █ (  1.0%)
                 Netgear RCE ▏   74 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   34 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   31 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2574 ███████████████████████████████████ ( 34.5%)
United Kingdom ▏ 1424 ███████████████████ ( 19.1%)
       Ireland ▏  887 ████████████ ( 11.9%)
   Netherlands ▏  568 ███████ (  7.6%)
        France ▏  451 ██████ (  6.0%)
         Japan ▏  424 █████ (  5.7%)
     Singapore ▏  342 ████ (  4.6%)
     Australia ▏  284 ███ (  3.8%)
       Germany ▏  264 ███ (  3.5%)
         India ▏  238 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-15 ▏   37 ████████████████████ ( 11.6%)
2025-11-16 ▏   62 ███████████████████████████████████ ( 19.4%)
2025-11-17 ▏   39 ██████████████████████ ( 12.2%)
2025-11-18 ▏   30 ████████████████ (  9.4%)
2025-11-19 ▏   48 ███████████████████████████ ( 15.0%)
2025-11-20 ▏   48 ███████████████████████████ ( 15.0%)
2025-11-21 ▏   52 █████████████████████████████ ( 16.3%)
2025-11-22 ▏    3 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!