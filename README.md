# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-513-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 513                      |
| Total Reports: 5,723                 |
| Unique Sources: 1,659                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1513 ███████████████████████████████████ ( 26.6%)
         HTTP Bad User Agent ▏ 1270 █████████████████████████████ ( 22.3%)
HTTP Admin Interface Probing ▏  619 ██████████████ ( 10.9%)
        HTTP Sensitive Files ▏  522 ████████████ (  9.2%)
         HTTP Wordpress Scan ▏  438 ██████████ (  7.7%)
       CVE-2017-9841 Exploit ▏  298 ██████ (  5.2%)
      HTTP Crawl Non Statics ▏  284 ██████ (  5.0%)
     HTTP Backdoors Attempts ▏  257 █████ (  4.5%)
            HTTP CVE Probing ▏  195 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  120 ██ (  2.1%)
      CVE-2022-41082 Exploit ▏   53 █ (  0.9%)
                 Netgear RCE ▏   39 █ (  0.7%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   19 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   17 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1612 ███████████████████████████████████ ( 32.9%)
United Kingdom ▏  851 ██████████████████ ( 17.4%)
       Ireland ▏  735 ███████████████ ( 15.0%)
        France ▏  372 ████████ (  7.6%)
     Singapore ▏  277 ██████ (  5.7%)
     Australia ▏  255 █████ (  5.2%)
         Japan ▏  239 █████ (  4.9%)
   Netherlands ▏  209 ████ (  4.3%)
       Germany ▏  185 ████ (  3.8%)
      Bulgaria ▏  158 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-20 ▏   49 █████████████████████████ ( 13.6%)
2025-09-21 ▏   61 ████████████████████████████████ ( 17.0%)
2025-09-22 ▏   40 █████████████████████ ( 11.1%)
2025-09-23 ▏   66 ███████████████████████████████████ ( 18.4%)
2025-09-24 ▏   41 █████████████████████ ( 11.4%)
2025-09-25 ▏   46 ████████████████████████ ( 12.8%)
2025-09-26 ▏   48 █████████████████████████ ( 13.4%)
2025-09-27 ▏    8 ████ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!