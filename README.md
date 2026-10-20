# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-403-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--10--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 403                      |
| Total Reports: 21,845                |
| Unique Sources: 5,678                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6570 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3653 ███████████████████ ( 16.9%)
HTTP Admin Interface Probing ▏ 2702 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2576 █████████████ ( 11.9%)
         HTTP Wordpress Scan ▏ 1538 ████████ (  7.1%)
      HTTP Crawl Non Statics ▏ 1250 ██████ (  5.8%)
            HTTP CVE Probing ▏  901 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  698 ███ (  3.2%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  345 █ (  1.6%)
      CVE-2022-41082 Exploit ▏  256 █ (  1.2%)
                 Netgear RCE ▏  176 █ (  0.8%)
 HTTP Path Traversal Probing ▏  149 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  104 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7123 ███████████████████████████████████ ( 41.7%)
United Kingdom ▏ 1898 █████████ ( 11.1%)
   Netherlands ▏ 1577 ███████ (  9.2%)
       Ireland ▏ 1282 ██████ (  7.5%)
        France ▏ 1227 ██████ (  7.2%)
     Singapore ▏ 1013 ████ (  5.9%)
        Canada ▏  796 ███ (  4.7%)
         Japan ▏  776 ███ (  4.5%)
       Germany ▏  756 ███ (  4.4%)
      Bulgaria ▏  642 ███ (  3.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-13 ▏   29 ████████ (  6.5%)
2026-10-14 ▏   42 ████████████ (  9.4%)
2026-10-15 ▏   55 ████████████████ ( 12.2%)
2026-10-16 ▏   46 █████████████ ( 10.2%)
2026-10-17 ▏  115 ██████████████████████████████████ ( 25.6%)
2026-10-18 ▏  118 ███████████████████████████████████ ( 26.3%)
2026-10-19 ▏   39 ███████████ (  8.7%)
2026-10-20 ▏    5 █ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!