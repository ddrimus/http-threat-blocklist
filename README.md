# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-521-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 521                      |
| Total Reports: 15,527                |
| Unique Sources: 4,146                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4622 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 2922 ██████████████████████ ( 18.9%)
HTTP Admin Interface Probing ▏ 1983 ███████████████ ( 12.8%)
        HTTP Sensitive Files ▏ 1476 ███████████ (  9.6%)
         HTTP Wordpress Scan ▏ 1369 ██████████ (  8.9%)
      HTTP Crawl Non Statics ▏  835 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  647 ████ (  4.2%)
            HTTP CVE Probing ▏  555 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  449 ███ (  2.9%)
      CVE-2022-41082 Exploit ▏  166 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  145 █ (  0.9%)
                 Netgear RCE ▏  122 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   57 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   48 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4831 ███████████████████████████████████ ( 37.9%)
United Kingdom ▏ 1772 ████████████ ( 13.9%)
       Ireland ▏ 1266 █████████ (  9.9%)
   Netherlands ▏  918 ██████ (  7.2%)
        France ▏  860 ██████ (  6.7%)
     Singapore ▏  733 █████ (  5.7%)
         Japan ▏  708 █████ (  5.6%)
        Canada ▏  622 ████ (  4.9%)
       Germany ▏  533 ███ (  4.2%)
     Australia ▏  507 ███ (  4.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-02 ▏   64 ███████████████████████████████ ( 15.8%)
2026-05-03 ▏   43 █████████████████████ ( 10.6%)
2026-05-04 ▏   46 ██████████████████████ ( 11.4%)
2026-05-05 ▏   53 ██████████████████████████ ( 13.1%)
2026-05-06 ▏   57 ████████████████████████████ ( 14.1%)
2026-05-07 ▏   68 █████████████████████████████████ ( 16.8%)
2026-05-08 ▏   71 ███████████████████████████████████ ( 17.5%)
2026-05-09 ▏    3 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!