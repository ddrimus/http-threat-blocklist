# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-269-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--07--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 269                      |
| Total Reports: 18,476                |
| Unique Sources: 4,882                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5545 ███████████████████████████████████ ( 30.2%)
         HTTP Bad User Agent ▏ 3330 █████████████████████ ( 18.1%)
HTTP Admin Interface Probing ▏ 2351 ██████████████ ( 12.8%)
        HTTP Sensitive Files ▏ 2018 ████████████ ( 11.0%)
         HTTP Wordpress Scan ▏ 1512 █████████ (  8.2%)
      HTTP Crawl Non Statics ▏ 1025 ██████ (  5.6%)
            HTTP CVE Probing ▏  703 ████ (  3.8%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  466 ██ (  2.5%)
      CVE-2022-41082 Exploit ▏  215 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  150 █ (  0.8%)
                 Netgear RCE ▏  150 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   84 █ (  0.5%)
 HTTP Path Traversal Probing ▏   69 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   59 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6037 ███████████████████████████████████ ( 40.1%)
United Kingdom ▏ 1822 ██████████ ( 12.1%)
   Netherlands ▏ 1331 ███████ (  8.8%)
       Ireland ▏ 1281 ███████ (  8.5%)
        France ▏ 1096 ██████ (  7.3%)
     Singapore ▏  808 ████ (  5.4%)
        Canada ▏  769 ████ (  5.1%)
         Japan ▏  728 ████ (  4.8%)
       Germany ▏  652 ███ (  4.3%)
     Australia ▏  516 ██ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-07-18 ▏   27 █████████████████████ ( 14.0%)
2026-07-19 ▏   32 ██████████████████████████ ( 16.6%)
2026-07-20 ▏   43 ███████████████████████████████████ ( 22.3%)
2026-07-21 ▏   22 █████████████████ ( 11.4%)
2026-07-22 ▏   15 ████████████ (  7.8%)
2026-07-23 ▏   21 █████████████████ ( 10.9%)
2026-07-24 ▏   33 ██████████████████████████ ( 17.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!