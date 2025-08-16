# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-526-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--16-brightgreen)](.)

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
| Total Reports: 3,436                 |
| Unique Sources: 1,090                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  850 ███████████████████████████████████ ( 24.8%)
         HTTP Bad User Agent ▏  778 ████████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  370 ███████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  285 ███████████ (  8.3%)
        HTTP Sensitive Files ▏  276 ███████████ (  8.1%)
       CVE-2017-9841 Exploit ▏  225 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  175 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  157 ██████ (  4.6%)
            HTTP CVE Probing ▏  108 ████ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  106 ████ (  3.1%)
      CVE-2022-41082 Exploit ▏   30 █ (  0.9%)
                 Netgear RCE ▏   23 █ (  0.7%)
 HTTP Path Traversal Probing ▏   20 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    9 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  928 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  572 █████████████████████ ( 19.1%)
       Ireland ▏  513 ███████████████████ ( 17.1%)
         Japan ▏  210 ███████ (  7.0%)
     Australia ▏  194 ███████ (  6.5%)
     Singapore ▏  168 ██████ (  5.6%)
        France ▏  125 ████ (  4.2%)
   Netherlands ▏  117 ████ (  3.9%)
       Germany ▏   91 ███ (  3.0%)
         China ▏   84 ███ (  2.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-09 ▏    2 █ (  1.0%)
2025-08-13 ▏   46 █████████████████ ( 23.7%)
2025-08-14 ▏   53 ████████████████████ ( 27.3%)
2025-08-15 ▏   91 ███████████████████████████████████ ( 46.9%)
2025-08-16 ▏    2 █ (  1.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!