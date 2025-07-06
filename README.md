# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-363-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 363                      |
| Total Reports: 808                   |
| Unique Sources: 363                  |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  223 ███████████████████████████████████ ( 27.6%)
                HTTP Probing ▏  201 ███████████████████████████████ ( 24.9%)
HTTP Admin Interface Probing ▏   84 █████████████ ( 10.4%)
        HTTP Sensitive Files ▏   64 ██████████ (  7.9%)
       CVE-2017-9841 Exploit ▏   51 ████████ (  6.3%)
         HTTP Wordpress Scan ▏   47 ███████ (  5.8%)
      HTTP Crawl Non Statics ▏   41 ██████ (  5.1%)
            HTTP CVE Probing ▏   26 ████ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏   23 ███ (  2.9%)
     HTTP Backdoors Attempts ▏   22 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏   12 █ (  1.5%)
                 Netgear RCE ▏    5 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.6%)
 HTTP Path Traversal Probing ▏    2 █ (  0.2%)
      CVE-2023-49103 Exploit ▏    1 █ (  0.1%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  253 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏  167 ███████████████████████ ( 22.7%)
       Ireland ▏  156 █████████████████████ ( 21.2%)
     Singapore ▏   35 ████ (  4.7%)
   Netherlands ▏   34 ████ (  4.6%)
       Germany ▏   23 ███ (  3.1%)
      Bulgaria ▏   22 ███ (  3.0%)
         China ▏   21 ██ (  2.8%)
          Iran ▏   14 █ (  1.9%)
         India ▏   12 █ (  1.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-29 ▏   63 ███████████████████████████ ( 13.5%)
2025-06-30 ▏   80 ███████████████████████████████████ ( 17.1%)
2025-07-01 ▏   64 ████████████████████████████ ( 13.7%)
2025-07-02 ▏   76 █████████████████████████████████ ( 16.3%)
2025-07-03 ▏   78 ██████████████████████████████████ ( 16.7%)
2025-07-04 ▏   39 █████████████████ (  8.4%)
2025-07-05 ▏   62 ███████████████████████████ ( 13.3%)
2025-07-06 ▏    5 ██ (  1.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!