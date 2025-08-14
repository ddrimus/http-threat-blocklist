# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-510-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--14-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 510                      |
| Total Reports: 3,295                 |
| Unique Sources: 1,050                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  816 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  744 ███████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  350 ███████████████ ( 10.7%)
         HTTP Wordpress Scan ▏  272 ███████████ (  8.3%)
        HTTP Sensitive Files ▏  255 ██████████ (  7.8%)
       CVE-2017-9841 Exploit ▏  225 █████████ (  6.9%)
     HTTP Backdoors Attempts ▏  172 ███████ (  5.2%)
      HTTP Crawl Non Statics ▏  151 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏  106 ████ (  3.2%)
            HTTP CVE Probing ▏  101 ████ (  3.1%)
      CVE-2022-41082 Exploit ▏   28 █ (  0.9%)
                 Netgear RCE ▏   22 █ (  0.7%)
 HTTP Path Traversal Probing ▏   20 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    9 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  884 ███████████████████████████████████ ( 30.7%)
United Kingdom ▏  559 ██████████████████████ ( 19.4%)
       Ireland ▏  498 ███████████████████ ( 17.3%)
         Japan ▏  207 ████████ (  7.2%)
     Australia ▏  185 ███████ (  6.4%)
     Singapore ▏  155 ██████ (  5.4%)
   Netherlands ▏  115 ████ (  4.0%)
        France ▏  100 ███ (  3.5%)
       Germany ▏   90 ███ (  3.1%)
         China ▏   82 ███ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-07 ▏   55 ██████████████████████████████████ ( 33.1%)
2025-08-08 ▏   56 ███████████████████████████████████ ( 33.7%)
2025-08-09 ▏    4 ██ (  2.4%)
2025-08-13 ▏   46 ████████████████████████████ ( 27.7%)
2025-08-14 ▏    5 ███ (  3.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!