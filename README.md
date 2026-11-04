# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-398-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--04-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 398                      |
| Total Reports: 22,397                |
| Unique Sources: 5,815                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6736 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3710 ███████████████████ ( 16.7%)
HTTP Admin Interface Probing ▏ 2779 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2656 █████████████ ( 12.0%)
         HTTP Wordpress Scan ▏ 1547 ████████ (  7.0%)
      HTTP Crawl Non Statics ▏ 1281 ██████ (  5.8%)
            HTTP CVE Probing ▏  932 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  736 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  374 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  264 █ (  1.2%)
                 Netgear RCE ▏  178 █ (  0.8%)
 HTTP Path Traversal Probing ▏  158 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  106 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7285 ███████████████████████████████████ ( 41.7%)
United Kingdom ▏ 1910 █████████ ( 10.9%)
   Netherlands ▏ 1607 ███████ (  9.2%)
       Ireland ▏ 1283 ██████ (  7.4%)
        France ▏ 1257 ██████ (  7.2%)
     Singapore ▏ 1044 █████ (  6.0%)
        Canada ▏  802 ███ (  4.6%)
       Germany ▏  788 ███ (  4.5%)
         Japan ▏  776 ███ (  4.4%)
      Bulgaria ▏  702 ███ (  4.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-28 ▏   35 ████████████████████████ ( 13.2%)
2026-10-29 ▏   35 ████████████████████████ ( 13.2%)
2026-10-30 ▏   49 █████████████████████████████████ ( 18.5%)
2026-10-31 ▏   51 ███████████████████████████████████ ( 19.2%)
2026-11-01 ▏   13 ████████ (  4.9%)
2026-11-02 ▏   42 ████████████████████████████ ( 15.8%)
2026-11-03 ▏   31 █████████████████████ ( 11.7%)
2026-11-04 ▏    9 ██████ (  3.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!