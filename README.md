# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-307-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 307                      |
| Total Reports: 19,400                |
| Unique Sources: 5,110                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5843 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3451 ████████████████████ ( 17.9%)
HTTP Admin Interface Probing ▏ 2427 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2173 █████████████ ( 11.3%)
         HTTP Wordpress Scan ▏ 1526 █████████ (  7.9%)
      HTTP Crawl Non Statics ▏ 1074 ██████ (  5.6%)
            HTTP CVE Probing ▏  757 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  522 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏  227 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  194 █ (  1.0%)
                 Netgear RCE ▏  161 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   95 █ (  0.5%)
 HTTP Path Traversal Probing ▏   75 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   62 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6415 ███████████████████████████████████ ( 40.8%)
United Kingdom ▏ 1843 ██████████ ( 11.7%)
   Netherlands ▏ 1437 ███████ (  9.1%)
       Ireland ▏ 1281 ██████ (  8.2%)
        France ▏ 1164 ██████ (  7.4%)
     Singapore ▏  831 ████ (  5.3%)
        Canada ▏  777 ████ (  4.9%)
         Japan ▏  745 ████ (  4.7%)
       Germany ▏  692 ███ (  4.4%)
      Bulgaria ▏  527 ██ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-19 ▏   26 █████████████████ ( 13.7%)
2026-08-20 ▏   52 ███████████████████████████████████ ( 27.4%)
2026-08-21 ▏   15 ██████████ (  7.9%)
2026-08-22 ▏   29 ███████████████████ ( 15.3%)
2026-08-23 ▏   30 ████████████████████ ( 15.8%)
2026-08-24 ▏   15 ██████████ (  7.9%)
2026-08-25 ▏   23 ███████████████ ( 12.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!