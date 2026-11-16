# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-367-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 367                      |
| Total Reports: 22,743                |
| Unique Sources: 5,913                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6848 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3746 ███████████████████ ( 16.6%)
HTTP Admin Interface Probing ▏ 2824 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2723 █████████████ ( 12.1%)
         HTTP Wordpress Scan ▏ 1551 ███████ (  6.9%)
      HTTP Crawl Non Statics ▏ 1305 ██████ (  5.8%)
            HTTP CVE Probing ▏  957 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  747 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  688 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  381 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  270 █ (  1.2%)
                 Netgear RCE ▏  182 █ (  0.8%)
 HTTP Path Traversal Probing ▏  158 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  107 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   68 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7425 ███████████████████████████████████ ( 41.9%)
United Kingdom ▏ 1920 █████████ ( 10.8%)
   Netherlands ▏ 1618 ███████ (  9.1%)
       Ireland ▏ 1283 ██████ (  7.2%)
        France ▏ 1278 ██████ (  7.2%)
     Singapore ▏ 1054 ████ (  6.0%)
        Canada ▏  807 ███ (  4.6%)
       Germany ▏  795 ███ (  4.5%)
         Japan ▏  777 ███ (  4.4%)
      Bulgaria ▏  747 ███ (  4.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-11-09 ▏   33 █████████████████████████ ( 15.6%)
2026-11-10 ▏   33 █████████████████████████ ( 15.6%)
2026-11-11 ▏   19 ██████████████ (  9.0%)
2026-11-12 ▏   23 █████████████████ ( 10.8%)
2026-11-13 ▏   25 ███████████████████ ( 11.8%)
2026-11-14 ▏   33 █████████████████████████ ( 15.6%)
2026-11-15 ▏   46 ███████████████████████████████████ ( 21.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!