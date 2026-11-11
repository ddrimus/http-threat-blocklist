# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-390-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--11-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 390                      |
| Total Reports: 22,601                |
| Unique Sources: 5,869                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6802 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3732 ███████████████████ ( 16.6%)
HTTP Admin Interface Probing ▏ 2805 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2695 █████████████ ( 12.0%)
         HTTP Wordpress Scan ▏ 1550 ███████ (  6.9%)
      HTTP Crawl Non Statics ▏ 1296 ██████ (  5.8%)
            HTTP CVE Probing ▏  944 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  744 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  688 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  380 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  268 █ (  1.2%)
                 Netgear RCE ▏  180 █ (  0.8%)
 HTTP Path Traversal Probing ▏  158 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  106 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7363 ███████████████████████████████████ ( 41.8%)
United Kingdom ▏ 1917 █████████ ( 10.9%)
   Netherlands ▏ 1614 ███████ (  9.2%)
       Ireland ▏ 1283 ██████ (  7.3%)
        France ▏ 1271 ██████ (  7.2%)
     Singapore ▏ 1047 ████ (  6.0%)
        Canada ▏  802 ███ (  4.6%)
       Germany ▏  790 ███ (  4.5%)
         Japan ▏  777 ███ (  4.4%)
      Bulgaria ▏  731 ███ (  4.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-11-04 ▏   26 █████████████████████████ ( 12.7%)
2026-11-05 ▏   35 ██████████████████████████████████ ( 17.2%)
2026-11-06 ▏   27 ██████████████████████████ ( 13.2%)
2026-11-07 ▏   20 ███████████████████ (  9.8%)
2026-11-08 ▏   23 ██████████████████████ ( 11.3%)
2026-11-09 ▏   36 ███████████████████████████████████ ( 17.6%)
2026-11-10 ▏   33 ████████████████████████████████ ( 16.2%)
2026-11-11 ▏    4 ███ (  2.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!