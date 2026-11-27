# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-360-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 360                      |
| Total Reports: 23,074                |
| Unique Sources: 6,009                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6942 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3789 ███████████████████ ( 16.6%)
HTTP Admin Interface Probing ▏ 2879 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2780 ██████████████ ( 12.1%)
         HTTP Wordpress Scan ▏ 1560 ███████ (  6.8%)
      HTTP Crawl Non Statics ▏ 1327 ██████ (  5.8%)
            HTTP CVE Probing ▏  977 ████ (  4.3%)
       CVE-2017-9841 Exploit ▏  751 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  691 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏  383 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  276 █ (  1.2%)
                 Netgear RCE ▏  187 █ (  0.8%)
 HTTP Path Traversal Probing ▏  162 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  107 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   70 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7527 ███████████████████████████████████ ( 41.9%)
United Kingdom ▏ 1949 █████████ ( 10.9%)
   Netherlands ▏ 1628 ███████ (  9.1%)
        France ▏ 1307 ██████ (  7.3%)
       Ireland ▏ 1284 █████ (  7.2%)
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

2026-11-20 ▏   24 █████████████████████ ( 12.8%)
2026-11-21 ▏   21 ██████████████████ ( 11.2%)
2026-11-22 ▏   25 █████████████████████ ( 13.4%)
2026-11-23 ▏   20 █████████████████ ( 10.7%)
2026-11-24 ▏   23 ████████████████████ ( 12.3%)
2026-11-25 ▏   33 ████████████████████████████ ( 17.6%)
2026-11-26 ▏   40 ███████████████████████████████████ ( 21.4%)
2026-11-27 ▏    1 █ (  0.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!