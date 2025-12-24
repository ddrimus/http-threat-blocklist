# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-451-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--24-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 451                      |
| Total Reports: 9,921                 |
| Unique Sources: 2,738                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2895 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2183 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1103 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏ 1072 ████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  628 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  417 █████ (  4.2%)
       CVE-2017-9841 Exploit ▏  400 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  392 ████ (  4.0%)
            HTTP CVE Probing ▏  349 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  139 █ (  1.4%)
      CVE-2022-41082 Exploit ▏   99 █ (  1.0%)
                 Netgear RCE ▏   80 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3012 ███████████████████████████████████ ( 35.3%)
United Kingdom ▏ 1603 ██████████████████ ( 18.8%)
       Ireland ▏  965 ███████████ ( 11.3%)
   Netherlands ▏  657 ███████ (  7.7%)
         Japan ▏  477 █████ (  5.6%)
        France ▏  467 █████ (  5.5%)
     Singapore ▏  427 ████ (  5.0%)
     Australia ▏  330 ███ (  3.9%)
       Germany ▏  307 ███ (  3.6%)
      Bulgaria ▏  276 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-17 ▏   33 ███████████████████████ ( 13.9%)
2025-12-18 ▏   49 ███████████████████████████████████ ( 20.6%)
2025-12-19 ▏   30 █████████████████████ ( 12.6%)
2025-12-20 ▏   29 ████████████████████ ( 12.2%)
2025-12-21 ▏   17 ████████████ (  7.1%)
2025-12-22 ▏   36 █████████████████████████ ( 15.1%)
2025-12-23 ▏   41 █████████████████████████████ ( 17.2%)
2025-12-24 ▏    3 ██ (  1.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!