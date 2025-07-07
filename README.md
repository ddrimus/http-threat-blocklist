# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-MEDIUM-yellow)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-388-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--07-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: MEDIUM                       |
| Active IPs: 388                      |
| Total Reports: 852                   |
| Unique Sources: 388                  |
+--------------------------------------+
```

*Threat levels: moderate activity detected.*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  244 ███████████████████████████████████ ( 28.7%)
                HTTP Probing ▏  211 ██████████████████████████████ ( 24.9%)
HTTP Admin Interface Probing ▏   85 ████████████ ( 10.0%)
        HTTP Sensitive Files ▏   66 █████████ (  7.8%)
       CVE-2017-9841 Exploit ▏   55 ███████ (  6.5%)
         HTTP Wordpress Scan ▏   47 ██████ (  5.5%)
      HTTP Crawl Non Statics ▏   41 █████ (  4.8%)
            HTTP CVE Probing ▏   28 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏   24 ███ (  2.8%)
     HTTP Backdoors Attempts ▏   22 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏   12 █ (  1.4%)
                 Netgear RCE ▏    5 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.6%)
 HTTP Path Traversal Probing ▏    2 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    2 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  271 ███████████████████████████████████ ( 35.1%)
United Kingdom ▏  178 ██████████████████████ ( 23.1%)
       Ireland ▏  156 ████████████████████ ( 20.2%)
     Singapore ▏   35 ████ (  4.5%)
   Netherlands ▏   34 ████ (  4.4%)
       Germany ▏   25 ███ (  3.2%)
         China ▏   23 ██ (  3.0%)
      Bulgaria ▏   23 ██ (  3.0%)
          Iran ▏   14 █ (  1.8%)
         India ▏   13 █ (  1.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-30 ▏   78 ███████████████████████████████████ ( 17.5%)
2025-07-01 ▏   64 ████████████████████████████ ( 14.3%)
2025-07-02 ▏   76 ██████████████████████████████████ ( 17.0%)
2025-07-03 ▏   78 ███████████████████████████████████ ( 17.5%)
2025-07-04 ▏   39 █████████████████ (  8.7%)
2025-07-05 ▏   62 ███████████████████████████ ( 13.9%)
2025-07-06 ▏   45 ████████████████████ ( 10.1%)
2025-07-07 ▏    4 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!