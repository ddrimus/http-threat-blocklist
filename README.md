# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-515-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--24-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 515                      |
| Total Reports: 7,017                 |
| Unique Sources: 2,019                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1928 ███████████████████████████████████ ( 27.6%)
         HTTP Bad User Agent ▏ 1548 ████████████████████████████ ( 22.2%)
HTTP Admin Interface Probing ▏  756 █████████████ ( 10.8%)
        HTTP Sensitive Files ▏  709 ████████████ ( 10.2%)
         HTTP Wordpress Scan ▏  482 ████████ (  6.9%)
       CVE-2017-9841 Exploit ▏  339 ██████ (  4.9%)
      HTTP Crawl Non Statics ▏  317 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  293 █████ (  4.2%)
            HTTP CVE Probing ▏  257 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.8%)
      CVE-2022-41082 Exploit ▏   72 █ (  1.0%)
                 Netgear RCE ▏   59 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   24 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2076 ███████████████████████████████████ ( 34.5%)
United Kingdom ▏ 1115 ██████████████████ ( 18.5%)
       Ireland ▏  782 █████████████ ( 13.0%)
        France ▏  409 ██████ (  6.8%)
   Netherlands ▏  376 ██████ (  6.2%)
     Singapore ▏  312 █████ (  5.2%)
         Japan ▏  293 ████ (  4.9%)
     Australia ▏  270 ████ (  4.5%)
       Germany ▏  215 ███ (  3.6%)
         India ▏  177 ██ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-17 ▏   47 ████████████████████ ( 10.4%)
2025-10-18 ▏   47 ████████████████████ ( 10.4%)
2025-10-19 ▏   69 ██████████████████████████████ ( 15.3%)
2025-10-20 ▏   54 ███████████████████████ ( 11.9%)
2025-10-21 ▏   76 █████████████████████████████████ ( 16.8%)
2025-10-22 ▏   73 ███████████████████████████████ ( 16.2%)
2025-10-23 ▏   80 ███████████████████████████████████ ( 17.7%)
2025-10-24 ▏    6 ██ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!