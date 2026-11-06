# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-387-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 387                      |
| Total Reports: 22,461                |
| Unique Sources: 5,832                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6761 ███████████████████████████████████ ( 30.4%)
         HTTP Bad User Agent ▏ 3713 ███████████████████ ( 16.7%)
HTTP Admin Interface Probing ▏ 2788 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2667 █████████████ ( 12.0%)
         HTTP Wordpress Scan ▏ 1548 ████████ (  6.9%)
      HTTP Crawl Non Statics ▏ 1282 ██████ (  5.8%)
            HTTP CVE Probing ▏  936 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  740 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  377 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  265 █ (  1.2%)
                 Netgear RCE ▏  180 █ (  0.8%)
 HTTP Path Traversal Probing ▏  158 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  106 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7306 ███████████████████████████████████ ( 41.8%)
United Kingdom ▏ 1913 █████████ ( 10.9%)
   Netherlands ▏ 1609 ███████ (  9.2%)
       Ireland ▏ 1283 ██████ (  7.3%)
        France ▏ 1261 ██████ (  7.2%)
     Singapore ▏ 1045 █████ (  6.0%)
        Canada ▏  802 ███ (  4.6%)
       Germany ▏  788 ███ (  4.5%)
         Japan ▏  777 ███ (  4.4%)
      Bulgaria ▏  713 ███ (  4.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-30 ▏   44 ██████████████████████████████ ( 17.3%)
2026-10-31 ▏   51 ███████████████████████████████████ ( 20.1%)
2026-11-01 ▏   13 ████████ (  5.1%)
2026-11-02 ▏   42 ████████████████████████████ ( 16.5%)
2026-11-03 ▏   31 █████████████████████ ( 12.2%)
2026-11-04 ▏   35 ████████████████████████ ( 13.8%)
2026-11-05 ▏   35 ████████████████████████ ( 13.8%)
2026-11-06 ▏    3 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!