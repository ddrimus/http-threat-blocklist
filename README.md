# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-345-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 345                      |
| Total Reports: 19,914                |
| Unique Sources: 5,255                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6004 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3498 ████████████████████ ( 17.7%)
HTTP Admin Interface Probing ▏ 2463 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2254 █████████████ ( 11.4%)
         HTTP Wordpress Scan ▏ 1526 ████████ (  7.7%)
      HTTP Crawl Non Statics ▏ 1096 ██████ (  5.5%)
            HTTP CVE Probing ▏  797 ████ (  4.0%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  567 ███ (  2.9%)
      CVE-2022-41082 Exploit ▏  235 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  230 █ (  1.2%)
                 Netgear RCE ▏  164 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   95 █ (  0.5%)
 HTTP Path Traversal Probing ▏   86 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6588 ███████████████████████████████████ ( 41.0%)
United Kingdom ▏ 1849 █████████ ( 11.5%)
   Netherlands ▏ 1481 ███████ (  9.2%)
       Ireland ▏ 1281 ██████ (  8.0%)
        France ▏ 1182 ██████ (  7.4%)
     Singapore ▏  853 ████ (  5.3%)
        Canada ▏  783 ████ (  4.9%)
         Japan ▏  761 ████ (  4.7%)
       Germany ▏  706 ███ (  4.4%)
      Bulgaria ▏  576 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-02 ▏   27 ███████████ (  8.5%)
2026-09-03 ▏   84 ███████████████████████████████████ ( 26.6%)
2026-09-04 ▏   36 ███████████████ ( 11.4%)
2026-09-05 ▏   34 ██████████████ ( 10.8%)
2026-09-06 ▏   45 ██████████████████ ( 14.2%)
2026-09-07 ▏   57 ███████████████████████ ( 18.0%)
2026-09-08 ▏   26 ██████████ (  8.2%)
2026-09-09 ▏    7 ██ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!