# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-364-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 364                      |
| Total Reports: 22,887                |
| Unique Sources: 5,954                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6887 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3766 ███████████████████ ( 16.6%)
HTTP Admin Interface Probing ▏ 2846 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2749 █████████████ ( 12.1%)
         HTTP Wordpress Scan ▏ 1554 ███████ (  6.8%)
      HTTP Crawl Non Statics ▏ 1313 ██████ (  5.8%)
            HTTP CVE Probing ▏  967 ████ (  4.3%)
       CVE-2017-9841 Exploit ▏  747 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  690 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏  381 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  272 █ (  1.2%)
                 Netgear RCE ▏  184 █ (  0.8%)
 HTTP Path Traversal Probing ▏  162 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  107 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   69 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7464 ███████████████████████████████████ ( 41.9%)
United Kingdom ▏ 1931 █████████ ( 10.8%)
   Netherlands ▏ 1624 ███████ (  9.1%)
       Ireland ▏ 1284 ██████ (  7.2%)
        France ▏ 1283 ██████ (  7.2%)
     Singapore ▏ 1060 ████ (  6.0%)
        Canada ▏  820 ███ (  4.6%)
       Germany ▏  799 ███ (  4.5%)
         Japan ▏  790 ███ (  4.4%)
      Bulgaria ▏  760 ███ (  4.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-11-13 ▏   23 █████████████████ (  9.3%)
2026-11-14 ▏   33 ████████████████████████ ( 13.4%)
2026-11-15 ▏   46 ██████████████████████████████████ ( 18.7%)
2026-11-16 ▏   38 ████████████████████████████ ( 15.4%)
2026-11-17 ▏   21 ███████████████ (  8.5%)
2026-11-18 ▏   47 ███████████████████████████████████ ( 19.1%)
2026-11-19 ▏   37 ███████████████████████████ ( 15.0%)
2026-11-20 ▏    1 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!