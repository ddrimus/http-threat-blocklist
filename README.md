# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-547-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--01-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 547                      |
| Total Reports: 2,698                 |
| Unique Sources: 904                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  673 ███████████████████████████████████ ( 25.0%)
         HTTP Bad User Agent ▏  623 ████████████████████████████████ ( 23.2%)
HTTP Admin Interface Probing ▏  289 ███████████████ ( 10.8%)
        HTTP Sensitive Files ▏  217 ███████████ (  8.1%)
         HTTP Wordpress Scan ▏  209 ██████████ (  7.8%)
       CVE-2017-9841 Exploit ▏  177 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  137 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  124 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏   85 ████ (  3.2%)
            HTTP CVE Probing ▏   81 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   26 █ (  1.0%)
                 Netgear RCE ▏   15 █ (  0.6%)
 HTTP Path Traversal Probing ▏   13 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    7 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  742 ███████████████████████████████████ ( 31.1%)
United Kingdom ▏  510 ████████████████████████ ( 21.4%)
       Ireland ▏  437 ████████████████████ ( 18.3%)
         Japan ▏  154 ███████ (  6.4%)
     Australia ▏  140 ██████ (  5.9%)
     Singapore ▏  114 █████ (  4.8%)
   Netherlands ▏  105 ████ (  4.4%)
       Germany ▏   73 ███ (  3.1%)
         China ▏   66 ███ (  2.8%)
      Bulgaria ▏   47 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-25 ▏   71 ███████████████████████████████ ( 17.0%)
2025-07-26 ▏   69 ██████████████████████████████ ( 16.5%)
2025-07-27 ▏   61 ██████████████████████████ ( 14.6%)
2025-07-28 ▏   65 ████████████████████████████ ( 15.6%)
2025-07-29 ▏   48 █████████████████████ ( 11.5%)
2025-07-30 ▏   12 █████ (  2.9%)
2025-07-31 ▏   80 ███████████████████████████████████ ( 19.2%)
2025-08-01 ▏   11 ████ (  2.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!