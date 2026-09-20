# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-373-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 373                      |
| Total Reports: 20,406                |
| Unique Sources: 5,380                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6150 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3538 ████████████████████ ( 17.5%)
HTTP Admin Interface Probing ▏ 2529 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2327 █████████████ ( 11.5%)
         HTTP Wordpress Scan ▏ 1529 ████████ (  7.6%)
      HTTP Crawl Non Statics ▏ 1122 ██████ (  5.5%)
            HTTP CVE Probing ▏  829 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.4%)
       CVE-2017-9841 Exploit ▏  610 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏  266 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  240 █ (  1.2%)
                 Netgear RCE ▏  169 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   96 █ (  0.5%)
 HTTP Path Traversal Probing ▏   93 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6738 ███████████████████████████████████ ( 41.3%)
United Kingdom ▏ 1862 █████████ ( 11.4%)
   Netherlands ▏ 1503 ███████ (  9.2%)
       Ireland ▏ 1282 ██████ (  7.9%)
        France ▏ 1195 ██████ (  7.3%)
     Singapore ▏  880 ████ (  5.4%)
        Canada ▏  787 ████ (  4.8%)
         Japan ▏  765 ███ (  4.7%)
       Germany ▏  714 ███ (  4.4%)
      Bulgaria ▏  582 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-13 ▏   31 ████████████████ (  9.0%)
2026-09-14 ▏   46 ████████████████████████ ( 13.4%)
2026-09-15 ▏   65 ███████████████████████████████████ ( 18.9%)
2026-09-16 ▏   58 ███████████████████████████████ ( 16.9%)
2026-09-17 ▏   45 ████████████████████████ ( 13.1%)
2026-09-18 ▏   40 █████████████████████ ( 11.6%)
2026-09-19 ▏   59 ███████████████████████████████ ( 17.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!