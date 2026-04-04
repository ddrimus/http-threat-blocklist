# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-410-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--04-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 410                      |
| Total Reports: 13,658                |
| Unique Sources: 3,612                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4048 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2685 ███████████████████████ ( 19.8%)
HTTP Admin Interface Probing ▏ 1698 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 1306 ███████████ (  9.6%)
         HTTP Wordpress Scan ▏ 1165 ██████████ (  8.6%)
      HTTP Crawl Non Statics ▏  669 █████ (  4.9%)
     HTTP Backdoors Attempts ▏  564 ████ (  4.2%)
            HTTP CVE Probing ▏  470 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  440 ███ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  143 █ (  1.1%)
                 Netgear RCE ▏  106 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   46 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4196 ███████████████████████████████████ ( 36.9%)
United Kingdom ▏ 1759 ██████████████ ( 15.5%)
       Ireland ▏ 1181 █████████ ( 10.4%)
   Netherlands ▏  822 ██████ (  7.2%)
        France ▏  692 █████ (  6.1%)
     Singapore ▏  677 █████ (  5.9%)
         Japan ▏  677 █████ (  5.9%)
       Germany ▏  491 ████ (  4.3%)
        Canada ▏  456 ███ (  4.0%)
     Australia ▏  434 ███ (  3.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-28 ▏   31 ███████████████████ ( 11.8%)
2026-03-29 ▏   26 ███████████████ (  9.9%)
2026-03-30 ▏   38 ███████████████████████ ( 14.5%)
2026-03-31 ▏   35 █████████████████████ ( 13.4%)
2026-04-01 ▏   36 ██████████████████████ ( 13.7%)
2026-04-02 ▏   57 ███████████████████████████████████ ( 21.8%)
2026-04-03 ▏   39 ███████████████████████ ( 14.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!