# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-465-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 465                      |
| Total Reports: 6,254                 |
| Unique Sources: 1,824                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1663 ███████████████████████████████████ ( 26.8%)
         HTTP Bad User Agent ▏ 1423 █████████████████████████████ ( 22.9%)
HTTP Admin Interface Probing ▏  657 █████████████ ( 10.6%)
        HTTP Sensitive Files ▏  587 ████████████ (  9.4%)
         HTTP Wordpress Scan ▏  452 █████████ (  7.3%)
       CVE-2017-9841 Exploit ▏  319 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  299 ██████ (  4.8%)
     HTTP Backdoors Attempts ▏  268 █████ (  4.3%)
            HTTP CVE Probing ▏  228 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  125 ██ (  2.0%)
      CVE-2022-41082 Exploit ▏   64 █ (  1.0%)
                 Netgear RCE ▏   45 █ (  0.7%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   24 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1825 ███████████████████████████████████ ( 34.1%)
United Kingdom ▏  954 ██████████████████ ( 17.8%)
       Ireland ▏  748 ██████████████ ( 14.0%)
        France ▏  376 ███████ (  7.0%)
     Singapore ▏  300 █████ (  5.6%)
   Netherlands ▏  268 █████ (  5.0%)
     Australia ▏  264 █████ (  4.9%)
         Japan ▏  263 █████ (  4.9%)
       Germany ▏  196 ███ (  3.7%)
      Bulgaria ▏  165 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-05 ▏   30 ██████████████████████ ( 11.4%)
2025-10-06 ▏   46 ███████████████████████████████████ ( 17.5%)
2025-10-07 ▏   36 ███████████████████████████ ( 13.7%)
2025-10-08 ▏   35 ██████████████████████████ ( 13.3%)
2025-10-09 ▏   42 ███████████████████████████████ ( 16.0%)
2025-10-10 ▏   30 ██████████████████████ ( 11.4%)
2025-10-11 ▏   43 ████████████████████████████████ ( 16.3%)
2025-10-12 ▏    1 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!