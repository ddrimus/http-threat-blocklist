# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-300-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--07--15-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 300                      |
| Total Reports: 18,233                |
| Unique Sources: 4,825                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5463 ███████████████████████████████████ ( 30.1%)
         HTTP Bad User Agent ▏ 3302 █████████████████████ ( 18.2%)
HTTP Admin Interface Probing ▏ 2330 ██████████████ ( 12.9%)
        HTTP Sensitive Files ▏ 1968 ████████████ ( 10.9%)
         HTTP Wordpress Scan ▏ 1502 █████████ (  8.3%)
      HTTP Crawl Non Statics ▏ 1012 ██████ (  5.6%)
            HTTP CVE Probing ▏  689 ████ (  3.8%)
     HTTP Backdoors Attempts ▏  686 ████ (  3.8%)
       CVE-2017-9841 Exploit ▏  459 ██ (  2.5%)
      CVE-2022-41082 Exploit ▏  211 █ (  1.2%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.8%)
                 Netgear RCE ▏  146 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   82 █ (  0.5%)
 HTTP Path Traversal Probing ▏   68 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   57 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5976 ███████████████████████████████████ ( 40.2%)
United Kingdom ▏ 1811 ██████████ ( 12.2%)
       Ireland ▏ 1281 ███████ (  8.6%)
   Netherlands ▏ 1277 ███████ (  8.6%)
        France ▏ 1046 ██████ (  7.0%)
     Singapore ▏  805 ████ (  5.4%)
        Canada ▏  768 ████ (  5.2%)
         Japan ▏  727 ████ (  4.9%)
       Germany ▏  644 ███ (  4.3%)
     Australia ▏  516 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-07-08 ▏   18 ███████████████████ ( 11.0%)
2026-07-09 ▏   19 ████████████████████ ( 11.7%)
2026-07-10 ▏   32 ███████████████████████████████████ ( 19.6%)
2026-07-11 ▏   26 ████████████████████████████ ( 16.0%)
2026-07-12 ▏   29 ███████████████████████████████ ( 17.8%)
2026-07-13 ▏   17 ██████████████████ ( 10.4%)
2026-07-14 ▏   20 █████████████████████ ( 12.3%)
2026-07-15 ▏    2 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!