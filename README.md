# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-520-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--05--08-brightgreen)](.)

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
| Total Reports: 15,465                |
| Unique Sources: 4,134                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4603 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 2915 ██████████████████████ ( 18.9%)
HTTP Admin Interface Probing ▏ 1973 ███████████████ ( 12.8%)
        HTTP Sensitive Files ▏ 1469 ███████████ (  9.5%)
         HTTP Wordpress Scan ▏ 1364 ██████████ (  8.9%)
      HTTP Crawl Non Statics ▏  833 ██████ (  5.4%)
     HTTP Backdoors Attempts ▏  646 ████ (  4.2%)
            HTTP CVE Probing ▏  551 ████ (  3.6%)
       CVE-2017-9841 Exploit ▏  448 ███ (  2.9%)
      CVE-2022-41082 Exploit ▏  164 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  145 █ (  0.9%)
                 Netgear RCE ▏  121 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   59 █ (  0.4%)
 HTTP Path Traversal Probing ▏   54 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   48 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4803 ███████████████████████████████████ ( 37.8%)
United Kingdom ▏ 1772 ████████████ ( 14.0%)
       Ireland ▏ 1266 █████████ ( 10.0%)
   Netherlands ▏  910 ██████ (  7.2%)
        France ▏  855 ██████ (  6.7%)
     Singapore ▏  730 █████ (  5.7%)
         Japan ▏  704 █████ (  5.5%)
        Canada ▏  622 ████ (  4.9%)
       Germany ▏  533 ███ (  4.2%)
     Australia ▏  507 ███ (  4.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-05-01 ▏   49 █████████████████████████ ( 12.4%)
2026-05-02 ▏   67 ██████████████████████████████████ ( 17.0%)
2026-05-03 ▏   43 ██████████████████████ ( 10.9%)
2026-05-04 ▏   46 ███████████████████████ ( 11.6%)
2026-05-05 ▏   53 ███████████████████████████ ( 13.4%)
2026-05-06 ▏   57 █████████████████████████████ ( 14.4%)
2026-05-07 ▏   68 ███████████████████████████████████ ( 17.2%)
2026-05-08 ▏   12 ██████ (  3.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!