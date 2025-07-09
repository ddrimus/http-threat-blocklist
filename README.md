# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-420-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 420                      |
| Total Reports: 1,013                 |
| Unique Sources: 433                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  276 ███████████████████████████████████ ( 27.4%)
                HTTP Probing ▏  254 ████████████████████████████████ ( 25.2%)
HTTP Admin Interface Probing ▏  104 █████████████ ( 10.3%)
        HTTP Sensitive Files ▏   81 ██████████ (  8.0%)
         HTTP Wordpress Scan ▏   62 ███████ (  6.1%)
       CVE-2017-9841 Exploit ▏   59 ███████ (  5.8%)
      HTTP Crawl Non Statics ▏   47 █████ (  4.7%)
            HTTP CVE Probing ▏   34 ████ (  3.4%)
     HTTP Backdoors Attempts ▏   30 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏   26 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏   13 █ (  1.3%)
 HTTP Path Traversal Probing ▏    9 █ (  0.9%)
                 Netgear RCE ▏    6 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.5%)
      CVE-2019-18935 Exploit ▏    3 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  313 ███████████████████████████████████ ( 34.2%)
United Kingdom ▏  233 ██████████████████████████ ( 25.5%)
       Ireland ▏  177 ███████████████████ ( 19.3%)
     Singapore ▏   38 ████ (  4.2%)
   Netherlands ▏   38 ████ (  4.2%)
         Japan ▏   27 ███ (  3.0%)
       Germany ▏   26 ██ (  2.8%)
         China ▏   23 ██ (  2.5%)
      Bulgaria ▏   23 ██ (  2.5%)
          Iran ▏   17 █ (  1.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-02 ▏   66 █████████████████████████ ( 14.5%)
2025-07-03 ▏   78 ██████████████████████████████ ( 17.1%)
2025-07-04 ▏   39 ███████████████ (  8.6%)
2025-07-05 ▏   62 ███████████████████████ ( 13.6%)
2025-07-06 ▏   45 █████████████████ (  9.9%)
2025-07-07 ▏   64 ████████████████████████ ( 14.1%)
2025-07-08 ▏   91 ███████████████████████████████████ ( 20.0%)
2025-07-09 ▏   10 ███ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!