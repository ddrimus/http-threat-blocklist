# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-500-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 500                      |
| Total Reports: 5,315                 |
| Unique Sources: 1,548                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1390 ███████████████████████████████████ ( 26.4%)
         HTTP Bad User Agent ▏ 1160 █████████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  567 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  480 ████████████ (  9.1%)
         HTTP Wordpress Scan ▏  417 ██████████ (  7.9%)
       CVE-2017-9841 Exploit ▏  291 ███████ (  5.5%)
      HTTP Crawl Non Statics ▏  269 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  244 ██████ (  4.6%)
            HTTP CVE Probing ▏  183 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  116 ██ (  2.2%)
      CVE-2022-41082 Exploit ▏   50 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
                 Netgear RCE ▏   37 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   17 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   15 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1471 ███████████████████████████████████ ( 32.3%)
United Kingdom ▏  789 ██████████████████ ( 17.3%)
       Ireland ▏  689 ████████████████ ( 15.1%)
        France ▏  367 ████████ (  8.1%)
     Singapore ▏  269 ██████ (  5.9%)
     Australia ▏  251 █████ (  5.5%)
         Japan ▏  239 █████ (  5.2%)
       Germany ▏  171 ████ (  3.8%)
   Netherlands ▏  163 ███ (  3.6%)
      Bulgaria ▏  150 ███ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-12 ▏   38 ██████████████████ ( 10.9%)
2025-09-13 ▏   34 ████████████████ (  9.8%)
2025-09-14 ▏   36 █████████████████ ( 10.3%)
2025-09-15 ▏   37 █████████████████ ( 10.6%)
2025-09-16 ▏   73 ███████████████████████████████████ ( 21.0%)
2025-09-17 ▏   51 ████████████████████████ ( 14.7%)
2025-09-18 ▏   73 ███████████████████████████████████ ( 21.0%)
2025-09-19 ▏    6 ██ (  1.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!