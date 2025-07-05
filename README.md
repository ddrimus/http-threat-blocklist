# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-339-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--05-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 339                      |
| Total Reports: 748                   |
| Unique Sources: 339                  |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  202 ███████████████████████████████████ ( 27.0%)
                HTTP Probing ▏  189 ████████████████████████████████ ( 25.3%)
HTTP Admin Interface Probing ▏   78 █████████████ ( 10.4%)
        HTTP Sensitive Files ▏   59 ██████████ (  7.9%)
       CVE-2017-9841 Exploit ▏   47 ████████ (  6.3%)
         HTTP Wordpress Scan ▏   45 ███████ (  6.0%)
      HTTP Crawl Non Statics ▏   38 ██████ (  5.1%)
   CVE-2018-20062 (Thinkphp) ▏   23 ███ (  3.1%)
            HTTP CVE Probing ▏   23 ███ (  3.1%)
     HTTP Backdoors Attempts ▏   20 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏   11 █ (  1.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.7%)
                 Netgear RCE ▏    4 █ (  0.5%)
 HTTP Path Traversal Probing ▏    2 █ (  0.3%)
      CVE-2023-49103 Exploit ▏    1 █ (  0.1%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  228 ███████████████████████████████████ ( 33.6%)
United Kingdom ▏  154 ███████████████████████ ( 22.7%)
       Ireland ▏  151 ███████████████████████ ( 22.2%)
     Singapore ▏   35 █████ (  5.2%)
   Netherlands ▏   29 ████ (  4.3%)
       Germany ▏   23 ███ (  3.4%)
         China ▏   19 ██ (  2.8%)
      Bulgaria ▏   17 ██ (  2.5%)
     Hong Kong ▏   12 █ (  1.8%)
         Japan ▏   11 █ (  1.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-28 ▏   42 ██████████████████ (  9.3%)
2025-06-29 ▏   64 ████████████████████████████ ( 14.2%)
2025-06-30 ▏   80 ███████████████████████████████████ ( 17.8%)
2025-07-01 ▏   64 ████████████████████████████ ( 14.2%)
2025-07-02 ▏   76 █████████████████████████████████ ( 16.9%)
2025-07-03 ▏   78 ██████████████████████████████████ ( 17.3%)
2025-07-04 ▏   39 █████████████████ (  8.7%)
2025-07-05 ▏    7 ███ (  1.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!