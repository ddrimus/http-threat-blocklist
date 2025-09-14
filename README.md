# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-530-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 530                      |
| Total Reports: 5,041                 |
| Unique Sources: 1,487                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1318 ███████████████████████████████████ ( 26.2%)
         HTTP Bad User Agent ▏ 1108 █████████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  535 ██████████████ ( 10.6%)
        HTTP Sensitive Files ▏  457 ████████████ (  9.1%)
         HTTP Wordpress Scan ▏  404 ██████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  285 ███████ (  5.7%)
      HTTP Crawl Non Statics ▏  255 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  236 ██████ (  4.7%)
            HTTP CVE Probing ▏  172 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  114 ███ (  2.3%)
      CVE-2022-41082 Exploit ▏   45 █ (  0.9%)
                 Netgear RCE ▏   35 █ (  0.7%)
 HTTP Path Traversal Probing ▏   29 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   17 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   15 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1327 ███████████████████████████████████ ( 30.7%)
United Kingdom ▏  762 ████████████████████ ( 17.6%)
       Ireland ▏  669 █████████████████ ( 15.5%)
        France ▏  364 █████████ (  8.4%)
     Australia ▏  250 ██████ (  5.8%)
     Singapore ▏  248 ██████ (  5.7%)
         Japan ▏  239 ██████ (  5.5%)
       Germany ▏  165 ████ (  3.8%)
   Netherlands ▏  153 ████ (  3.5%)
      Bulgaria ▏  150 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-07 ▏   54 █████████████████████████████████ ( 19.6%)
2025-09-08 ▏   57 ███████████████████████████████████ ( 20.7%)
2025-09-09 ▏   57 ███████████████████████████████████ ( 20.7%)
2025-09-10 ▏    8 ████ (  2.9%)
2025-09-11 ▏   26 ███████████████ (  9.4%)
2025-09-12 ▏   38 ███████████████████████ ( 13.8%)
2025-09-13 ▏   34 ████████████████████ ( 12.3%)
2025-09-14 ▏    2 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!