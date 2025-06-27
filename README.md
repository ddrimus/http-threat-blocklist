# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-127-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 127                      |
| Total Reports: 239                   |
| Unique Sources: 127                  |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏   70 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏   65 ████████████████████████████████ ( 27.2%)
HTTP Admin Interface Probing ▏   25 ████████████ ( 10.5%)
        HTTP Sensitive Files ▏   17 ████████ (  7.1%)
         HTTP Wordpress Scan ▏   15 ███████ (  6.3%)
      HTTP Crawl Non Statics ▏   14 ███████ (  5.9%)
   CVE-2018-20062 (Thinkphp) ▏    7 ███ (  2.9%)
       CVE-2017-9841 Exploit ▏    7 ███ (  2.9%)
            HTTP CVE Probing ▏    6 ███ (  2.5%)
     HTTP Backdoors Attempts ▏    6 ███ (  2.5%)
                 Netgear RCE ▏    3 █ (  1.3%)
       CVE-2021-26086 (Jira) ▏    2 █ (  0.8%)
      CVE-2022-41082 Exploit ▏    2 █ (  0.8%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   65 ███████████████████████████████████ ( 29.7%)
       Ireland ▏   64 ██████████████████████████████████ ( 29.2%)
United Kingdom ▏   41 ██████████████████████ ( 18.7%)
     Singapore ▏   13 ███████ (  5.9%)
   Netherlands ▏   11 █████ (  5.0%)
       Germany ▏    7 ███ (  3.2%)
          Iran ▏    6 ███ (  2.7%)
         India ▏    6 ███ (  2.7%)
   South Korea ▏    3 █ (  1.4%)
     Hong Kong ▏    3 █ (  1.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-23 ▏   29 ████████████ ( 12.1%)
2025-06-24 ▏   84 ███████████████████████████████████ ( 35.1%)
2025-06-25 ▏   65 ███████████████████████████ ( 27.2%)
2025-06-26 ▏   55 ██████████████████████ ( 23.0%)
2025-06-27 ▏    6 ██ (  2.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!