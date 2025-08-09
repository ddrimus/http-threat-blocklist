# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-575-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 575                      |
| Total Reports: 3,242                 |
| Unique Sources: 1,033                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  802 ███████████████████████████████████ ( 24.8%)
         HTTP Bad User Agent ▏  732 ███████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  343 ██████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  270 ███████████ (  8.4%)
        HTTP Sensitive Files ▏  250 ██████████ (  7.7%)
       CVE-2017-9841 Exploit ▏  221 █████████ (  6.8%)
     HTTP Backdoors Attempts ▏  171 ███████ (  5.3%)
      HTTP Crawl Non Statics ▏  147 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏  104 ████ (  3.2%)
            HTTP CVE Probing ▏  101 ████ (  3.1%)
      CVE-2022-41082 Exploit ▏   28 █ (  0.9%)
                 Netgear RCE ▏   22 █ (  0.7%)
 HTTP Path Traversal Probing ▏   20 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  874 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  554 ██████████████████████ ( 19.6%)
       Ireland ▏  493 ███████████████████ ( 17.4%)
         Japan ▏  203 ████████ (  7.2%)
     Australia ▏  185 ███████ (  6.5%)
     Singapore ▏  155 ██████ (  5.5%)
   Netherlands ▏  114 ████ (  4.0%)
       Germany ▏   87 ███ (  3.1%)
        France ▏   85 ███ (  3.0%)
         China ▏   82 ███ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-02 ▏    1 █ (  0.2%)
2025-08-03 ▏   81 ████████████████████████████████ ( 18.0%)
2025-08-04 ▏   79 ███████████████████████████████ ( 17.6%)
2025-08-05 ▏   77 ██████████████████████████████ ( 17.1%)
2025-08-06 ▏   88 ███████████████████████████████████ ( 19.6%)
2025-08-07 ▏   65 █████████████████████████ ( 14.5%)
2025-08-08 ▏   56 ██████████████████████ ( 12.5%)
2025-08-09 ▏    2 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!