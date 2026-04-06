# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-411-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--04--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 411                      |
| Total Reports: 13,736                |
| Unique Sources: 3,636                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 4072 ███████████████████████████████████ ( 29.8%)
         HTTP Bad User Agent ▏ 2694 ███████████████████████ ( 19.7%)
HTTP Admin Interface Probing ▏ 1713 ██████████████ ( 12.5%)
        HTTP Sensitive Files ▏ 1310 ███████████ (  9.6%)
         HTTP Wordpress Scan ▏ 1179 ██████████ (  8.6%)
      HTTP Crawl Non Statics ▏  673 █████ (  4.9%)
     HTTP Backdoors Attempts ▏  568 ████ (  4.2%)
            HTTP CVE Probing ▏  473 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  440 ███ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  144 █ (  1.1%)
                 Netgear RCE ▏  106 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   46 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4210 ███████████████████████████████████ ( 36.8%)
United Kingdom ▏ 1759 ██████████████ ( 15.4%)
       Ireland ▏ 1184 █████████ ( 10.3%)
   Netherlands ▏  823 ██████ (  7.2%)
        France ▏  700 █████ (  6.1%)
     Singapore ▏  678 █████ (  5.9%)
         Japan ▏  677 █████ (  5.9%)
       Germany ▏  494 ████ (  4.3%)
        Canada ▏  469 ███ (  4.1%)
     Australia ▏  450 ███ (  3.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-30 ▏   36 ██████████████████████ ( 12.8%)
2026-03-31 ▏   35 █████████████████████ ( 12.5%)
2026-04-01 ▏   36 ██████████████████████ ( 12.8%)
2026-04-02 ▏   57 ███████████████████████████████████ ( 20.3%)
2026-04-03 ▏   39 ███████████████████████ ( 13.9%)
2026-04-04 ▏   34 ████████████████████ ( 12.1%)
2026-04-05 ▏   42 █████████████████████████ ( 14.9%)
2026-04-06 ▏    2 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!