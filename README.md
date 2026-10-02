# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-406-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--10--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 406                      |
| Total Reports: 21,009                |
| Unique Sources: 5,501                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6317 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3589 ███████████████████ ( 17.2%)
HTTP Admin Interface Probing ▏ 2605 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2431 █████████████ ( 11.7%)
         HTTP Wordpress Scan ▏ 1529 ████████ (  7.3%)
      HTTP Crawl Non Statics ▏ 1190 ██████ (  5.7%)
            HTTP CVE Probing ▏  861 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.3%)
       CVE-2017-9841 Exploit ▏  647 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  302 █ (  1.4%)
      CVE-2022-41082 Exploit ▏  246 █ (  1.2%)
                 Netgear RCE ▏  171 █ (  0.8%)
 HTTP Path Traversal Probing ▏  104 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏   96 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   65 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 6871 ███████████████████████████████████ ( 41.4%)
United Kingdom ▏ 1876 █████████ ( 11.3%)
   Netherlands ▏ 1558 ███████ (  9.4%)
       Ireland ▏ 1282 ██████ (  7.7%)
        France ▏ 1203 ██████ (  7.2%)
     Singapore ▏  946 ████ (  5.7%)
        Canada ▏  787 ████ (  4.7%)
         Japan ▏  766 ███ (  4.6%)
       Germany ▏  731 ███ (  4.4%)
      Bulgaria ▏  592 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-09-25 ▏   48 ██████████████████ ( 12.8%)
2026-09-26 ▏   40 ███████████████ ( 10.7%)
2026-09-27 ▏   52 ████████████████████ ( 13.9%)
2026-09-28 ▏   47 ██████████████████ ( 12.5%)
2026-09-29 ▏   62 ███████████████████████ ( 16.5%)
2026-09-30 ▏   28 ██████████ (  7.5%)
2026-10-01 ▏   91 ███████████████████████████████████ ( 24.3%)
2026-10-02 ▏    7 ██ (  1.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!