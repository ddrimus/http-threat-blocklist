# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-547-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--11-brightgreen)](.)

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
| Total Reports: 4,941                 |
| Unique Sources: 1,461                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1290 ███████████████████████████████████ ( 26.2%)
         HTTP Bad User Agent ▏ 1085 █████████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  529 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  445 ████████████ (  9.0%)
         HTTP Wordpress Scan ▏  397 ██████████ (  8.1%)
       CVE-2017-9841 Exploit ▏  278 ███████ (  5.6%)
      HTTP Crawl Non Statics ▏  250 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  232 ██████ (  4.7%)
            HTTP CVE Probing ▏  167 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  112 ███ (  2.3%)
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

 United States ▏ 1301 ███████████████████████████████████ ( 30.7%)
United Kingdom ▏  741 ███████████████████ ( 17.5%)
       Ireland ▏  649 █████████████████ ( 15.3%)
        France ▏  360 █████████ (  8.5%)
     Australia ▏  250 ██████ (  5.9%)
     Singapore ▏  244 ██████ (  5.8%)
         Japan ▏  239 ██████ (  5.6%)
       Germany ▏  162 ████ (  3.8%)
   Netherlands ▏  153 ████ (  3.6%)
      Bulgaria ▏  142 ███ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-04 ▏   48 ████████████████████████████ ( 14.5%)
2025-09-05 ▏   52 ██████████████████████████████ ( 15.7%)
2025-09-06 ▏   49 ████████████████████████████ ( 14.8%)
2025-09-07 ▏   60 ███████████████████████████████████ ( 18.1%)
2025-09-08 ▏   57 █████████████████████████████████ ( 17.2%)
2025-09-09 ▏   57 █████████████████████████████████ ( 17.2%)
2025-09-10 ▏    8 ████ (  2.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!