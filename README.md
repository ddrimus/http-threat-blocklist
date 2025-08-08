# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-574-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--08-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 574                      |
| Total Reports: 3,189                 |
| Unique Sources: 1,020                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  790 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  717 ███████████████████████████████ ( 22.6%)
HTTP Admin Interface Probing ▏  338 ██████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  265 ███████████ (  8.3%)
        HTTP Sensitive Files ▏  246 ██████████ (  7.7%)
       CVE-2017-9841 Exploit ▏  220 █████████ (  6.9%)
     HTTP Backdoors Attempts ▏  166 ███████ (  5.2%)
      HTTP Crawl Non Statics ▏  144 ██████ (  4.5%)
   CVE-2018-20062 (Thinkphp) ▏  104 ████ (  3.3%)
            HTTP CVE Probing ▏  100 ████ (  3.1%)
      CVE-2022-41082 Exploit ▏   27 █ (  0.8%)
                 Netgear RCE ▏   22 █ (  0.7%)
 HTTP Path Traversal Probing ▏   19 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  860 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  548 ██████████████████████ ( 19.7%)
       Ireland ▏  481 ███████████████████ ( 17.3%)
         Japan ▏  196 ███████ (  7.0%)
     Australia ▏  185 ███████ (  6.6%)
     Singapore ▏  151 ██████ (  5.4%)
   Netherlands ▏  114 ████ (  4.1%)
       Germany ▏   87 ███ (  3.1%)
         China ▏   82 ███ (  2.9%)
        France ▏   79 ███ (  2.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-01 ▏   83 █████████████████████████████████ ( 16.9%)
2025-08-02 ▏   13 █████ (  2.6%)
2025-08-03 ▏   81 ████████████████████████████████ ( 16.5%)
2025-08-04 ▏   79 ███████████████████████████████ ( 16.1%)
2025-08-05 ▏   77 ██████████████████████████████ ( 15.7%)
2025-08-06 ▏   88 ███████████████████████████████████ ( 17.9%)
2025-08-07 ▏   65 █████████████████████████ ( 13.2%)
2025-08-08 ▏    5 █ (  1.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!