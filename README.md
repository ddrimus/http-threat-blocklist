# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-462-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 462                      |
| Total Reports: 6,145                 |
| Unique Sources: 1,796                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1634 ███████████████████████████████████ ( 26.8%)
         HTTP Bad User Agent ▏ 1391 █████████████████████████████ ( 22.8%)
HTTP Admin Interface Probing ▏  650 █████████████ ( 10.6%)
        HTTP Sensitive Files ▏  575 ████████████ (  9.4%)
         HTTP Wordpress Scan ▏  450 █████████ (  7.4%)
       CVE-2017-9841 Exploit ▏  311 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  295 ██████ (  4.8%)
     HTTP Backdoors Attempts ▏  264 █████ (  4.3%)
            HTTP CVE Probing ▏  222 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  122 ██ (  2.0%)
      CVE-2022-41082 Exploit ▏   63 █ (  1.0%)
                 Netgear RCE ▏   44 █ (  0.7%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   24 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1788 ███████████████████████████████████ ( 34.0%)
United Kingdom ▏  942 ██████████████████ ( 17.9%)
       Ireland ▏  740 ██████████████ ( 14.1%)
        France ▏  376 ███████ (  7.1%)
     Singapore ▏  289 █████ (  5.5%)
     Australia ▏  260 █████ (  4.9%)
         Japan ▏  258 █████ (  4.9%)
   Netherlands ▏  247 ████ (  4.7%)
       Germany ▏  194 ███ (  3.7%)
      Bulgaria ▏  165 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-02 ▏   31 ███████████████████████ ( 13.1%)
2025-10-03 ▏   31 ███████████████████████ ( 13.1%)
2025-10-04 ▏   19 ██████████████ (  8.1%)
2025-10-05 ▏   31 ███████████████████████ ( 13.1%)
2025-10-06 ▏   46 ███████████████████████████████████ ( 19.5%)
2025-10-07 ▏   36 ███████████████████████████ ( 15.3%)
2025-10-08 ▏   35 ██████████████████████████ ( 14.8%)
2025-10-09 ▏    7 █████ (  3.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!