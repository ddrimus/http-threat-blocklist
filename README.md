# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-210-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 210                      |
| Total Reports: 406                   |
| Unique Sources: 210                  |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  119 ███████████████████████████████████ ( 29.3%)
                HTTP Probing ▏  103 ██████████████████████████████ ( 25.4%)
HTTP Admin Interface Probing ▏   41 ████████████ ( 10.1%)
        HTTP Sensitive Files ▏   26 ███████ (  6.4%)
         HTTP Wordpress Scan ▏   25 ███████ (  6.2%)
      HTTP Crawl Non Statics ▏   22 ██████ (  5.4%)
       CVE-2017-9841 Exploit ▏   22 ██████ (  5.4%)
   CVE-2018-20062 (Thinkphp) ▏   12 ███ (  3.0%)
            HTTP CVE Probing ▏   12 ███ (  3.0%)
     HTTP Backdoors Attempts ▏   11 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏    6 █ (  1.5%)
                 Netgear RCE ▏    4 █ (  1.0%)
       CVE-2021-26086 (Jira) ▏    2 █ (  0.5%)
      CVE-2019-18935 Exploit ▏    1 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  130 ███████████████████████████████████ ( 35.1%)
       Ireland ▏   91 ████████████████████████ ( 24.6%)
United Kingdom ▏   64 █████████████████ ( 17.3%)
     Singapore ▏   24 ██████ (  6.5%)
       Germany ▏   16 ████ (  4.3%)
   Netherlands ▏   13 ███ (  3.5%)
         China ▏   12 ███ (  3.2%)
          Iran ▏    8 ██ (  2.2%)
         India ▏    6 █ (  1.6%)
     Indonesia ▏    6 █ (  1.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-23 ▏   29 ████████████ (  7.1%)
2025-06-24 ▏   84 ███████████████████████████████████ ( 20.7%)
2025-06-25 ▏   65 ███████████████████████████ ( 16.0%)
2025-06-26 ▏   55 ██████████████████████ ( 13.5%)
2025-06-27 ▏   64 ██████████████████████████ ( 15.8%)
2025-06-28 ▏   43 █████████████████ ( 10.6%)
2025-06-29 ▏   64 ██████████████████████████ ( 15.8%)
2025-06-30 ▏    2 █ (  0.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!