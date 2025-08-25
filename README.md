# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-549-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 549                      |
| Total Reports: 4,077                 |
| Unique Sources: 1,221                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1021 ███████████████████████████████████ ( 25.1%)
         HTTP Bad User Agent ▏  911 ███████████████████████████████ ( 22.4%)
HTTP Admin Interface Probing ▏  445 ███████████████ ( 11.0%)
        HTTP Sensitive Files ▏  355 ████████████ (  8.7%)
         HTTP Wordpress Scan ▏  333 ███████████ (  8.2%)
       CVE-2017-9841 Exploit ▏  258 ████████ (  6.3%)
      HTTP Crawl Non Statics ▏  197 ██████ (  4.8%)
     HTTP Backdoors Attempts ▏  195 ██████ (  4.8%)
            HTTP CVE Probing ▏  130 ████ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  108 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏   33 █ (  0.8%)
                 Netgear RCE ▏   27 █ (  0.7%)
 HTTP Path Traversal Probing ▏   25 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   11 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1085 ███████████████████████████████████ ( 30.6%)
United Kingdom ▏  623 ████████████████████ ( 17.6%)
       Ireland ▏  558 ██████████████████ ( 15.7%)
        France ▏  252 ████████ (  7.1%)
     Australia ▏  241 ███████ (  6.8%)
         Japan ▏  233 ███████ (  6.6%)
     Singapore ▏  199 ██████ (  5.6%)
   Netherlands ▏  124 ████ (  3.5%)
      Bulgaria ▏  122 ███ (  3.4%)
       Germany ▏  110 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-18 ▏   72 ██████████████████████████████ ( 14.9%)
2025-08-19 ▏   84 ███████████████████████████████████ ( 17.4%)
2025-08-20 ▏   70 █████████████████████████████ ( 14.5%)
2025-08-21 ▏   65 ███████████████████████████ ( 13.4%)
2025-08-22 ▏   65 ███████████████████████████ ( 13.4%)
2025-08-23 ▏   64 ██████████████████████████ ( 13.2%)
2025-08-24 ▏   50 ████████████████████ ( 10.3%)
2025-08-25 ▏   14 █████ (  2.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!