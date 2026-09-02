# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-315-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 315                      |
| Total Reports: 19,598                |
| Unique Sources: 5,171                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5907 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3480 ████████████████████ ( 17.9%)
HTTP Admin Interface Probing ▏ 2438 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2205 █████████████ ( 11.3%)
         HTTP Wordpress Scan ▏ 1526 █████████ (  7.8%)
      HTTP Crawl Non Statics ▏ 1081 ██████ (  5.6%)
            HTTP CVE Probing ▏  768 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  538 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏  231 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  208 █ (  1.1%)
                 Netgear RCE ▏  161 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   95 █ (  0.5%)
 HTTP Path Traversal Probing ▏   80 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   62 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6495 ███████████████████████████████████ ( 40.9%)
United Kingdom ▏ 1845 █████████ ( 11.6%)
   Netherlands ▏ 1444 ███████ (  9.1%)
       Ireland ▏ 1281 ██████ (  8.1%)
        France ▏ 1176 ██████ (  7.4%)
     Singapore ▏  837 ████ (  5.3%)
        Canada ▏  780 ████ (  4.9%)
         Japan ▏  761 ████ (  4.8%)
       Germany ▏  697 ███ (  4.4%)
      Bulgaria ▏  550 ██ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-26 ▏   31 ███████████████████████████████ ( 15.7%)
2026-08-27 ▏   21 █████████████████████ ( 10.6%)
2026-08-28 ▏   24 ████████████████████████ ( 12.1%)
2026-08-29 ▏   30 ██████████████████████████████ ( 15.2%)
2026-08-30 ▏   35 ███████████████████████████████████ ( 17.7%)
2026-08-31 ▏   30 ██████████████████████████████ ( 15.2%)
2026-09-01 ▏   26 ██████████████████████████ ( 13.1%)
2026-09-02 ▏    1 █ (  0.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!