# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-411-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--08-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 411                      |
| Total Reports: 929                   |
| Unique Sources: 411                  |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  264 ███████████████████████████████████ ( 28.5%)
                HTTP Probing ▏  228 ██████████████████████████████ ( 24.6%)
HTTP Admin Interface Probing ▏   94 ████████████ ( 10.2%)
        HTTP Sensitive Files ▏   72 █████████ (  7.8%)
         HTTP Wordpress Scan ▏   57 ███████ (  6.2%)
       CVE-2017-9841 Exploit ▏   55 ███████ (  5.9%)
      HTTP Crawl Non Statics ▏   45 █████ (  4.9%)
            HTTP CVE Probing ▏   31 ████ (  3.3%)
     HTTP Backdoors Attempts ▏   29 ███ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏   24 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏   12 █ (  1.3%)
                 Netgear RCE ▏    5 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.5%)
      CVE-2019-18935 Exploit ▏    3 █ (  0.3%)
 HTTP Path Traversal Probing ▏    2 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  292 ███████████████████████████████████ ( 34.7%)
United Kingdom ▏  191 ██████████████████████ ( 22.7%)
       Ireland ▏  174 ████████████████████ ( 20.7%)
   Netherlands ▏   37 ████ (  4.4%)
     Singapore ▏   35 ████ (  4.2%)
       Germany ▏   26 ███ (  3.1%)
         Japan ▏   24 ██ (  2.9%)
         China ▏   23 ██ (  2.7%)
      Bulgaria ▏   23 ██ (  2.7%)
          Iran ▏   17 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-01 ▏   56 █████████████████████████ ( 12.8%)
2025-07-02 ▏   76 ██████████████████████████████████ ( 17.4%)
2025-07-03 ▏   78 ███████████████████████████████████ ( 17.8%)
2025-07-04 ▏   39 █████████████████ (  8.9%)
2025-07-05 ▏   62 ███████████████████████████ ( 14.2%)
2025-07-06 ▏   45 ████████████████████ ( 10.3%)
2025-07-07 ▏   64 ████████████████████████████ ( 14.6%)
2025-07-08 ▏   17 ███████ (  3.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!