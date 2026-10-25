# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-412-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--10--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 412                      |
| Total Reports: 22,036                |
| Unique Sources: 5,727                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6625 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3671 ███████████████████ ( 16.8%)
HTTP Admin Interface Probing ▏ 2732 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2604 █████████████ ( 11.9%)
         HTTP Wordpress Scan ▏ 1541 ████████ (  7.0%)
      HTTP Crawl Non Statics ▏ 1260 ██████ (  5.8%)
            HTTP CVE Probing ▏  909 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  719 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  358 █ (  1.6%)
      CVE-2022-41082 Exploit ▏  258 █ (  1.2%)
                 Netgear RCE ▏  176 █ (  0.8%)
 HTTP Path Traversal Probing ▏  150 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  104 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7189 ███████████████████████████████████ ( 41.8%)
United Kingdom ▏ 1900 █████████ ( 11.0%)
   Netherlands ▏ 1582 ███████ (  9.2%)
       Ireland ▏ 1283 ██████ (  7.5%)
        France ▏ 1237 ██████ (  7.2%)
     Singapore ▏ 1019 ████ (  5.9%)
        Canada ▏  802 ███ (  4.7%)
         Japan ▏  776 ███ (  4.5%)
       Germany ▏  767 ███ (  4.5%)
      Bulgaria ▏  648 ███ (  3.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-18 ▏  102 ███████████████████████████████████ ( 30.3%)
2026-10-19 ▏   39 █████████████ ( 11.6%)
2026-10-20 ▏   36 ████████████ ( 10.7%)
2026-10-21 ▏   51 █████████████████ ( 15.1%)
2026-10-22 ▏   39 █████████████ ( 11.6%)
2026-10-23 ▏   41 ██████████████ ( 12.2%)
2026-10-24 ▏   24 ████████ (  7.1%)
2026-10-25 ▏    5 █ (  1.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!