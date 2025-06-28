# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-152-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--28-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 152                      |
| Total Reports: 298                   |
| Unique Sources: 152                  |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏   81 ███████████████████████████████████ ( 27.2%)
         HTTP Bad User Agent ▏   79 ██████████████████████████████████ ( 26.5%)
HTTP Admin Interface Probing ▏   33 ██████████████ ( 11.1%)
         HTTP Wordpress Scan ▏   20 ████████ (  6.7%)
        HTTP Sensitive Files ▏   19 ████████ (  6.4%)
      HTTP Crawl Non Statics ▏   17 ███████ (  5.7%)
       CVE-2017-9841 Exploit ▏   13 █████ (  4.4%)
            HTTP CVE Probing ▏    9 ███ (  3.0%)
     HTTP Backdoors Attempts ▏    9 ███ (  3.0%)
   CVE-2018-20062 (Thinkphp) ▏    8 ███ (  2.7%)
                 Netgear RCE ▏    4 █ (  1.3%)
      CVE-2022-41082 Exploit ▏    4 █ (  1.3%)
       CVE-2021-26086 (Jira) ▏    2 █ (  0.7%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   90 ███████████████████████████████████ ( 33.0%)
       Ireland ▏   78 ██████████████████████████████ ( 28.6%)
United Kingdom ▏   45 █████████████████ ( 16.5%)
     Singapore ▏   16 ██████ (  5.9%)
   Netherlands ▏   11 ████ (  4.0%)
         China ▏    9 ███ (  3.3%)
       Germany ▏    8 ███ (  2.9%)
          Iran ▏    6 ██ (  2.2%)
         India ▏    6 ██ (  2.2%)
     Indonesia ▏    4 █ (  1.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-23 ▏   29 ████████████ (  9.7%)
2025-06-24 ▏   84 ███████████████████████████████████ ( 28.2%)
2025-06-25 ▏   65 ███████████████████████████ ( 21.8%)
2025-06-26 ▏   55 ██████████████████████ ( 18.5%)
2025-06-27 ▏   64 ██████████████████████████ ( 21.5%)
2025-06-28 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!