# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-397-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--09--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 397                      |
| Total Reports: 20,687                |
| Unique Sources: 5,432                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6226 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3565 ████████████████████ ( 17.4%)
HTTP Admin Interface Probing ▏ 2566 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2368 █████████████ ( 11.5%)
         HTTP Wordpress Scan ▏ 1529 ████████ (  7.5%)
      HTTP Crawl Non Statics ▏ 1149 ██████ (  5.6%)
            HTTP CVE Probing ▏  848 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.3%)
       CVE-2017-9841 Exploit ▏  629 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  286 █ (  1.4%)
      CVE-2022-41082 Exploit ▏  243 █ (  1.2%)
                 Netgear RCE ▏  169 █ (  0.8%)
 HTTP Path Traversal Probing ▏   98 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏   96 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   63 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6806 ███████████████████████████████████ ( 41.4%)
United Kingdom ▏ 1868 █████████ ( 11.4%)
   Netherlands ▏ 1530 ███████ (  9.3%)
       Ireland ▏ 1282 ██████ (  7.8%)
        France ▏ 1196 ██████ (  7.3%)
     Singapore ▏  889 ████ (  5.4%)
        Canada ▏  787 ████ (  4.8%)
         Japan ▏  766 ███ (  4.7%)
       Germany ▏  722 ███ (  4.4%)
      Bulgaria ▏  587 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-19 ▏   55 ██████████████████████████████ ( 16.4%)
2026-09-20 ▏   46 █████████████████████████ ( 13.7%)
2026-09-21 ▏   47 █████████████████████████ ( 14.0%)
2026-09-22 ▏   64 ███████████████████████████████████ ( 19.0%)
2026-09-23 ▏   35 ███████████████████ ( 10.4%)
2026-09-24 ▏   32 █████████████████ (  9.5%)
2026-09-25 ▏   52 ████████████████████████████ ( 15.5%)
2026-09-26 ▏    5 ██ (  1.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!