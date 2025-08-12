# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-573-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--12-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 573                      |
| Total Reports: 3,460                 |
| Unique Sources: 1,074                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  857 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  779 ███████████████████████████████ ( 22.6%)
HTTP Admin Interface Probing ▏  368 ███████████████ ( 10.7%)
         HTTP Wordpress Scan ▏  296 ████████████ (  8.6%)
        HTTP Sensitive Files ▏  271 ███████████ (  7.9%)
       CVE-2017-9841 Exploit ▏  226 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  188 ███████ (  5.5%)
      HTTP Crawl Non Statics ▏  163 ██████ (  4.7%)
   CVE-2018-20062 (Thinkphp) ▏  104 ████ (  3.0%)
            HTTP CVE Probing ▏  104 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   30 █ (  0.9%)
                 Netgear RCE ▏   22 █ (  0.6%)
 HTTP Path Traversal Probing ▏   21 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  915 ███████████████████████████████████ ( 30.2%)
United Kingdom ▏  584 ██████████████████████ ( 19.3%)
       Ireland ▏  544 ████████████████████ ( 18.0%)
         Japan ▏  218 ████████ (  7.2%)
     Australia ▏  205 ███████ (  6.8%)
     Singapore ▏  161 ██████ (  5.3%)
   Netherlands ▏  116 ████ (  3.8%)
        France ▏  111 ████ (  3.7%)
       Germany ▏   87 ███ (  2.9%)
         China ▏   84 ███ (  2.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-05 ▏   77 ███████████████████████████ ( 15.2%)
2025-08-06 ▏   88 ███████████████████████████████ ( 17.4%)
2025-08-07 ▏   65 ███████████████████████ ( 12.8%)
2025-08-08 ▏   56 ████████████████████ ( 11.1%)
2025-08-09 ▏   60 █████████████████████ ( 11.9%)
2025-08-10 ▏   54 ███████████████████ ( 10.7%)
2025-08-11 ▏   98 ███████████████████████████████████ ( 19.4%)
2025-08-12 ▏    8 ██ (  1.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!