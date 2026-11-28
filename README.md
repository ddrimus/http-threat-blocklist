# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-363-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--28-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 363                      |
| Total Reports: 23,097                |
| Unique Sources: 6,019                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6948 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3794 ███████████████████ ( 16.6%)
HTTP Admin Interface Probing ▏ 2883 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2781 ██████████████ ( 12.1%)
         HTTP Wordpress Scan ▏ 1562 ███████ (  6.8%)
      HTTP Crawl Non Statics ▏ 1329 ██████ (  5.8%)
            HTTP CVE Probing ▏  978 ████ (  4.3%)
       CVE-2017-9841 Exploit ▏  751 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  692 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏  383 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  277 █ (  1.2%)
                 Netgear RCE ▏  187 █ (  0.8%)
 HTTP Path Traversal Probing ▏  162 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  107 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   70 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7538 ███████████████████████████████████ ( 42.0%)
United Kingdom ▏ 1949 █████████ ( 10.8%)
   Netherlands ▏ 1629 ███████ (  9.1%)
        France ▏ 1308 ██████ (  7.3%)
       Ireland ▏ 1284 █████ (  7.1%)
     Singapore ▏ 1071 ████ (  6.0%)
        Canada ▏  820 ███ (  4.6%)
       Germany ▏  802 ███ (  4.5%)
         Japan ▏  790 ███ (  4.4%)
      Bulgaria ▏  775 ███ (  4.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-11-21 ▏   20 █████████████████ ( 10.8%)
2026-11-22 ▏   25 █████████████████████ ( 13.5%)
2026-11-23 ▏   20 █████████████████ ( 10.8%)
2026-11-24 ▏   23 ████████████████████ ( 12.4%)
2026-11-25 ▏   33 ████████████████████████████ ( 17.8%)
2026-11-26 ▏   40 ███████████████████████████████████ ( 21.6%)
2026-11-27 ▏   22 ███████████████████ ( 11.9%)
2026-11-28 ▏    2 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!