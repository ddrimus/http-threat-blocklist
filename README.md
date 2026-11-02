# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-400-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--11--02-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 400                      |
| Total Reports: 22,327                |
| Unique Sources: 5,796                |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 6711 ███████████████████████████████████ ( 30.3%)
         HTTP Bad User Agent ▏ 3703 ███████████████████ ( 16.7%)
HTTP Admin Interface Probing ▏ 2770 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 2643 █████████████ ( 11.9%)
         HTTP Wordpress Scan ▏ 1546 ████████ (  7.0%)
      HTTP Crawl Non Statics ▏ 1278 ██████ (  5.8%)
            HTTP CVE Probing ▏  930 ████ (  4.2%)
       CVE-2017-9841 Exploit ▏  731 ███ (  3.3%)
     HTTP Backdoors Attempts ▏  687 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏  370 █ (  1.7%)
      CVE-2022-41082 Exploit ▏  263 █ (  1.2%)
                 Netgear RCE ▏  178 █ (  0.8%)
 HTTP Path Traversal Probing ▏  158 █ (  0.7%)
       CVE-2021-26086 (Jira) ▏  106 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   67 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 7268 ███████████████████████████████████ ( 41.8%)
United Kingdom ▏ 1909 █████████ ( 11.0%)
   Netherlands ▏ 1601 ███████ (  9.2%)
       Ireland ▏ 1283 ██████ (  7.4%)
        France ▏ 1248 ██████ (  7.2%)
     Singapore ▏ 1035 ████ (  5.9%)
        Canada ▏  802 ███ (  4.6%)
       Germany ▏  784 ███ (  4.5%)
         Japan ▏  776 ███ (  4.5%)
      Bulgaria ▏  694 ███ (  4.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-10-26 ▏   31 █████████████████████ ( 12.3%)
2026-10-27 ▏   27 ██████████████████ ( 10.7%)
2026-10-28 ▏   35 ████████████████████████ ( 13.8%)
2026-10-29 ▏   35 ████████████████████████ ( 13.8%)
2026-10-30 ▏   49 █████████████████████████████████ ( 19.4%)
2026-10-31 ▏   51 ███████████████████████████████████ ( 20.2%)
2026-11-01 ▏   13 ████████ (  5.1%)
2026-11-02 ▏   12 ████████ (  4.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!