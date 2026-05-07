# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-520-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--07-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 520                      |
| Total Reports: 15,386                |
| Unique Sources: 4,120                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4581 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 2911 ██████████████████████ ( 19.0%)
HTTP Admin Interface Probing ▏ 1956 ██████████████ ( 12.8%)
        HTTP Sensitive Files ▏ 1463 ███████████ (  9.6%)
         HTTP Wordpress Scan ▏ 1351 ██████████ (  8.8%)
      HTTP Crawl Non Statics ▏  826 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  640 ████ (  4.2%)
            HTTP CVE Probing ▏  548 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  448 ███ (  2.9%)
      CVE-2022-41082 Exploit ▏  164 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  145 █ (  0.9%)
                 Netgear RCE ▏  120 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   54 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   48 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4763 ███████████████████████████████████ ( 37.7%)
United Kingdom ▏ 1772 █████████████ ( 14.0%)
       Ireland ▏ 1266 █████████ ( 10.0%)
   Netherlands ▏  910 ██████ (  7.2%)
        France ▏  849 ██████ (  6.7%)
     Singapore ▏  727 █████ (  5.8%)
         Japan ▏  695 █████ (  5.5%)
        Canada ▏  612 ████ (  4.8%)
       Germany ▏  530 ███ (  4.2%)
     Australia ▏  507 ███ (  4.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-04-30 ▏   53 ███████████████████████████ ( 13.9%)
2026-05-01 ▏   62 ████████████████████████████████ ( 16.2%)
2026-05-02 ▏   67 ███████████████████████████████████ ( 17.5%)
2026-05-03 ▏   43 ██████████████████████ ( 11.3%)
2026-05-04 ▏   46 ████████████████████████ ( 12.0%)
2026-05-05 ▏   53 ███████████████████████████ ( 13.9%)
2026-05-06 ▏   57 █████████████████████████████ ( 14.9%)
2026-05-07 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!