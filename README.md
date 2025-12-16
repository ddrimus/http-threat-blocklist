# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-474-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 474                      |
| Total Reports: 9,643                 |
| Unique Sources: 2,657                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2808 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2126 ██████████████████████████ ( 22.2%)
        HTTP Sensitive Files ▏ 1078 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏ 1035 ████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  609 ███████ (  6.3%)
      HTTP Crawl Non Statics ▏  401 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  392 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  383 ████ (  4.0%)
            HTTP CVE Probing ▏  337 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  138 █ (  1.4%)
      CVE-2022-41082 Exploit ▏   97 █ (  1.0%)
                 Netgear RCE ▏   76 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   40 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2925 ███████████████████████████████████ ( 35.3%)
United Kingdom ▏ 1569 ██████████████████ ( 18.9%)
       Ireland ▏  942 ███████████ ( 11.4%)
   Netherlands ▏  631 ███████ (  7.6%)
         Japan ▏  468 █████ (  5.6%)
        France ▏  466 █████ (  5.6%)
     Singapore ▏  415 ████ (  5.0%)
     Australia ▏  311 ███ (  3.7%)
       Germany ▏  302 ███ (  3.6%)
      Bulgaria ▏  266 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-09 ▏   21 ████████████████ (  9.1%)
2025-12-10 ▏   35 ███████████████████████████ ( 15.2%)
2025-12-11 ▏   39 ██████████████████████████████ ( 17.0%)
2025-12-12 ▏   27 █████████████████████ ( 11.7%)
2025-12-13 ▏   34 ██████████████████████████ ( 14.8%)
2025-12-14 ▏   27 █████████████████████ ( 11.7%)
2025-12-15 ▏   45 ███████████████████████████████████ ( 19.6%)
2025-12-16 ▏    2 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!