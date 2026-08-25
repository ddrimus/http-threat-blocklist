# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-302-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 302                      |
| Total Reports: 19,377                |
| Unique Sources: 5,105                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5836 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3448 ████████████████████ ( 17.9%)
HTTP Admin Interface Probing ▏ 2424 ██████████████ ( 12.6%)
        HTTP Sensitive Files ▏ 2170 █████████████ ( 11.3%)
         HTTP Wordpress Scan ▏ 1526 █████████ (  7.9%)
      HTTP Crawl Non Statics ▏ 1072 ██████ (  5.6%)
            HTTP CVE Probing ▏  756 ████ (  3.9%)
     HTTP Backdoors Attempts ▏  687 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  521 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏  226 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  193 █ (  1.0%)
                 Netgear RCE ▏  161 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   95 █ (  0.5%)
 HTTP Path Traversal Probing ▏   74 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   62 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6402 ███████████████████████████████████ ( 40.8%)
United Kingdom ▏ 1843 ██████████ ( 11.7%)
   Netherlands ▏ 1437 ███████ (  9.2%)
       Ireland ▏ 1281 ███████ (  8.2%)
        France ▏ 1163 ██████ (  7.4%)
     Singapore ▏  828 ████ (  5.3%)
        Canada ▏  777 ████ (  5.0%)
         Japan ▏  745 ████ (  4.7%)
       Germany ▏  688 ███ (  4.4%)
      Bulgaria ▏  525 ██ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-08-18 ▏   32 █████████████████████ ( 15.4%)
2026-08-19 ▏   35 ███████████████████████ ( 16.8%)
2026-08-20 ▏   52 ███████████████████████████████████ ( 25.0%)
2026-08-21 ▏   15 ██████████ (  7.2%)
2026-08-22 ▏   29 ███████████████████ ( 13.9%)
2026-08-23 ▏   30 ████████████████████ ( 14.4%)
2026-08-24 ▏   15 ██████████ (  7.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!