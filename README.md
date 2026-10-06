# cloud-ips

Public IP prefix lists from cloud platforms, CDNs, crawler bots, uptime
monitors, vulnerability scanners, anonymisers and threat-intelligence feeds.
Files are refreshed automatically by
[ip-fetcher](https://github.com/jonhadfield/ip-fetcher) and are intended for
firewall allowlists, blocklists and network filters.

## Contents

##### last updated: Tue, 06 Oct 2026 00:00:37 UTC

| File | Provider | Category | Source |
| --- | --- | --- | --- |
| [ahrefs.json](ahrefs.json) | AhrefsBot | crawlers | [source](https://api.ahrefs.com/v3/public/crawler-ip-ranges) |
| [airvpn.json](airvpn.json) | AirVPN | anonymiser | [source](https://airvpn.org/) |
| [akamai.txt](akamai.txt) | Akamai | cdn | [source](https://techdocs.akamai.com/property-manager/docs/origin-ip-access-control) |
| [alibaba.json](alibaba.json) | Alibaba | hosting | [source](https://www.alibaba.com/) |
| [amazonbot.json](amazonbot.json) | Amazonbot | crawlers | [source](https://developer.amazon.com/amazonbot) |
| [anthropic.json](anthropic.json) | Anthropic Crawler Bots | crawlers | [source](https://claude.com/crawling/bots.json) |
| [applebot.json](applebot.json) | Applebot | crawlers | [source](https://support.apple.com/en-us/119829) |
| [asndrop.json](asndrop.json) | Spamhaus ASN-DROP | threat | [source](https://www.spamhaus.org/blocklists/do-not-route-or-peer/) |
| [atlassian.json](atlassian.json) | Atlassian | saas | [source](https://ip-ranges.atlassian.com/) |
| [aws.json](aws.json) | Amazon Web Services | cloud | [source](https://docs.aws.amazon.com/vpc/latest/userguide/aws-ip-ranges.html) |
| [azure.json](azure.json) | Microsoft Azure | cloud | [source](https://www.microsoft.com/en-gb/download/details.aspx?id=56519) |
| [blocklistde.txt](blocklistde.txt) | Blocklist.de | threat | [source](https://www.blocklist.de/en/index.html) |
| [betterstack.txt](betterstack.txt) | Better Stack | monitoring | [source](https://betterstack.com/docs/uptime/ip-addresses/) |
| [binarydefense.txt](binarydefense.txt) | Binary Defense | threat | [source](https://www.binarydefense.com/) |
| [bingbot.json](bingbot.json) | Bingbot | crawlers | [source](https://www.bing.com/webmasters/help/how-to-verify-bingbot-3905dc26) |
| [bunny.json](bunny.json) | Bunny.net | cdn | [source](https://bunny.net/) |
| [cachefly.txt](cachefly.txt) | CacheFly | cdn | [source](https://cachefly.cachefly.net/ips/cdn.txt) |
| [ccbot.json](ccbot.json) | Common Crawl CCBot | crawlers | [source](https://commoncrawl.org/ccbot) |
| [cdn77.json](cdn77.json) | CDN77 | cdn | [source](https://www.cdn77.com/) |
| [cinsscore.txt](cinsscore.txt) | CINS Army List | threat | [source](https://cinsscore.com/) |
| [circleci.json](circleci.json) | CircleCI | saas | [source](https://circleci.com/docs/ip-ranges/) |
| [checkly.json](checkly.json) | Checkly | monitoring | [source](https://www.checklyhq.com/docs/monitoring/allowlisting/) |
| [cloudflare.json](cloudflare.json) | Cloudflare | cdn | [source](https://www.cloudflare.com/en-gb/ips/) |
| [contabo.json](contabo.json) | Contabo | hosting | [source](https://contabo.com/) |
| [cymru.json](cymru.json) | Team Cymru Bogons | bogons | [source](https://www.team-cymru.com/bogon-reference) |
| [datadog.json](datadog.json) | Datadog | saas | [source](https://docs.datadoghq.com/api/latest/ip-ranges/) |
| [detectify.txt](detectify.txt) | Detectify | scanner | [source](https://docs.detectify.com/network-setup/scanner-ip-addresses) |
| [digitalocean.csv](digitalocean.csv) | DigitalOcean | hosting | [source](https://www.digitalocean.com/) |
| [dshield.txt](dshield.txt) | DShield Recommended Block List | threat | [source](https://www.dshield.org/) |
| [duckduckbot.json](duckduckbot.json) | DuckDuckBot | crawlers | [source](https://duckduckgo.com/duckduckbot.json) |
| [emergingthreats.txt](emergingthreats.txt) | Emerging Threats Compromised IPs | threat | [source](https://rules.emergingthreats.net/blockrules/) |
| [fastly.json](fastly.json) | Fastly | cdn | [source](https://www.fastly.com/documentation/reference/api/utils/public-ip-list/) |
| [feodo.txt](feodo.txt) | abuse.ch Feodo Tracker | threat | [source](https://feodotracker.abuse.ch/blocklist/) |
| [flyio.json](flyio.json) | Fly.io | hosting | [source](https://fly.io/) |
| [gcp.json](gcp.json) | Google Cloud Platform | cloud | [source](https://cloud.google.com/compute/docs/faq#find_ip_range) |
| [gcore.json](gcore.json) | Gcore CDN | cdn | [source](https://gcore.com/) |
| [github.txt](github.txt) | GitHub | hosting | [source](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-githubs-ip-addresses) |
| [gitlab.txt](gitlab.txt) | GitLab | saas | [source](https://docs.gitlab.com/ee/user/gitlab_com/#ip-range) |
| [google.json](google.json) | Google | hosting | [source](https://support.google.com/a/answer/10026322) |
| [googlebot.json](googlebot.json) | Google Crawler Bots | crawlers | [source](https://developers.google.com/search/docs/crawling-indexing/verifying-googlebot) |
| [googlesc.json](googlesc.json) | Google Special Crawlers | crawlers | [source](https://developers.google.com/search/docs/crawling-indexing/verifying-googlebot) |
| [googleutf.json](googleutf.json) | Google User-Triggered Fetchers | crawlers | [source](https://developers.google.com/search/docs/crawling-indexing/verifying-googlebot) |
| [grafana.json](grafana.json) | Grafana Synthetic Monitoring | monitoring | [source](https://grafana.com/docs/grafana-cloud/testing/synthetic-monitoring/create-checks/public-probes/) |
| [greensnow.txt](greensnow.txt) | GreenSnow | threat | [source](https://greensnow.co/) |
| [hetzner.json](hetzner.json) | Hetzner | hosting | [source](https://www.hetzner.com/) |
| [hetrixtools.txt](hetrixtools.txt) | HetrixTools | monitoring | [source](https://docs.hetrixtools.com/uptime-monitoring-ip-addresses/) |
| [huawei.json](huawei.json) | Huawei Cloud | hosting | [source](https://www.huaweicloud.com/) |
| [ibmcloud.json](ibmcloud.json) | IBM Cloud | hosting | [source](https://www.ibm.com/cloud) |
| [icloudpr.csv](icloudpr.csv) | iCloud Private Relay | anonymiser | [source](https://support.apple.com/en-us/HT212614) |
| [imperva.json](imperva.json) | Imperva | security | [source](https://docs.imperva.com/bundle/cloud-application-security/page/more/restricting-direct-access.htm) |
| [intercom.json](intercom.json) | Intercom | saas | [source](https://developers.intercom.com/docs/build-an-integration/learn-more/ip-allowlisting) |
| [intruder.txt](intruder.txt) | Intruder | scanner | [source](https://help.intruder.io/en/articles/1635683-what-ips-do-i-need-to-add-to-my-allowlist) |
| [invicti.txt](invicti.txt) | Invicti | scanner | [source](https://docs.invicti.com/ip/trustlist-us) |
| [ipsum.txt](ipsum.txt) | IPsum | threat | [source](https://github.com/stamparm/ipsum) |
| [ivpn.json](ivpn.json) | IVPN | anonymiser | [source](https://www.ivpn.net/) |
| [leaseweb.json](leaseweb.json) | Leaseweb | hosting | [source](https://www.leaseweb.com/) |
| [linode.json](linode.json) | Linode | hosting | [source](https://www.linode.com/) |
| [m247.json](m247.json) | M247 | hosting | [source](https://www.m247.com/) |
| [m365.json](m365.json) | Microsoft 365 | saas | [source](https://learn.microsoft.com/en-us/microsoft-365/enterprise/microsoft-365-ip-web-service) |
| [mullvad.json](mullvad.json) | Mullvad | anonymiser | [source](https://mullvad.net/en/servers) |
| [newrelic.json](newrelic.json) | New Relic Synthetics | monitoring | [source](https://docs.newrelic.com/docs/synthetics/synthetic-monitoring/administration/synthetic-public-minion-ips/) |
| [nodeping.txt](nodeping.txt) | NodePing | monitoring | [source](https://nodeping.com/FAQ) |
| [oci.json](oci.json) | Oracle Cloud Infrastructure | hosting | [source](https://docs.oracle.com/en-us/iaas/Content/General/Concepts/addressranges.htm) |
| [ohdear.txt](ohdear.txt) | Oh Dear | monitoring | [source](https://ohdear.app/docs/faq/what-ips-does-oh-dear-monitor-from) |
| [okta.json](okta.json) | Okta | saas | [source](https://help.okta.com/en-us/content/topics/security/ip-address-allow-listing.htm) |
| [openai.json](openai.json) | OpenAI Bots | crawlers | [source](https://platform.openai.com/docs/bots) |
| [ovh.json](ovh.json) | OVH | hosting | [source](https://www.ovh.com/) |
| [pingdom.json](pingdom.json) | Pingdom | monitoring | [source](https://www.pingdom.com/) |
| [perplexitybot.json](perplexitybot.json) | PerplexityBot | crawlers | [source](https://www.perplexity.com/perplexitybot.json) |
| [qualys.json](qualys.json) | Qualys | scanner | [source](https://docs.qualys.com/en/vm/latest/help/external_scanner_ips.htm) |
| [quiccloud.txt](quiccloud.txt) | QUIC.cloud | cdn | [source](https://www.quic.cloud/ips) |
| [rapid7.txt](rapid7.txt) | Rapid7 InsightAppSec | scanner | [source](https://docs.rapid7.com/insightappsec/allowlist-cloud-engine-ips/) |
| [render.json](render.json) | Render | hosting | [source](https://render.com/) |
| [salesforce.json](salesforce.json) | Salesforce | saas | [source](https://help.salesforce.com/s/articleView?id=000384438&type=1) |
| [scaleway.json](scaleway.json) | Scaleway | hosting | [source](https://www.scaleway.com/) |
| [sentry.txt](sentry.txt) | Sentry Uptime | monitoring | [source](https://docs.sentry.io/security-legal-pii/security/ip-ranges/) |
| [site24x7.json](site24x7.json) | Site24x7 | monitoring | [source](https://www.site24x7.com/multi-location-web-site-monitoring.html) |
| [spamhaus.json](spamhaus.json) | Spamhaus DROP | threat | [source](https://www.spamhaus.org/blocklists/do-not-route-or-peer/) |
| [statuscake.json](statuscake.json) | StatusCake | monitoring | [source](https://www.statuscake.com/) |
| [stopforumspam.txt](stopforumspam.txt) | StopForumSpam | threat | [source](https://www.stopforumspam.com/) |
| [stripe.json](stripe.json) | Stripe | saas | [source](https://docs.stripe.com/ips) |
| [surfshark.json](surfshark.json) | Surfshark | anonymiser | [source](https://surfshark.com/) |
| [tenable.json](tenable.json) | Tenable Cloud Scanners | scanner | [source](https://docs.tenable.com/vulnerability-management/Content/Settings/Sensors/CloudSensors.htm) |
| [telegram.txt](telegram.txt) | Telegram | saas | [source](https://core.telegram.org/resources/cidr.txt) |
| [tencent.json](tencent.json) | Tencent Cloud | hosting | [source](https://www.tencentcloud.com/) |
| [threatfox.json](threatfox.json) | abuse.ch ThreatFox | threat | [source](https://threatfox.abuse.ch/) |
| [tor.txt](tor.txt) | Tor Exit Nodes | anonymiser | [source](https://check.torproject.org/) |
| [updown.json](updown.json) | updown.io | monitoring | [source](https://updown.io/api) |
| [uptimerobot.txt](uptimerobot.txt) | UptimeRobot | monitoring | [source](https://uptimerobot.com/help/locations/) |
| [uptrends.json](uptrends.json) | Uptrends | monitoring | [source](https://www.uptrends.com/support/kb/account/ip-addresses-for-whitelisting) |
| [vultr.json](vultr.json) | Vultr | hosting | [source](https://www.vultr.com/) |
| [x4bnet.json](x4bnet.json) | X4BNet VPN | anonymiser | [source](https://github.com/X4BNet/lists_vpn) |
| [xpanse.txt](xpanse.txt) | Cortex Xpanse | scanner | [source](https://cortex-docs.paloaltonetworks.com/cortex-xpanse/reference/scanning-activity) |
| [zoom.txt](zoom.txt) | Zoom | saas | [source](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0060548) |
| [zscaler.json](zscaler.json) | Zscaler | security | [source](https://www.zscaler.com) |


## Usage

Pick a file from the table, download it, and apply the prefixes to your
firewall or filter. Formats are JSON, plain text or CSV depending on the
upstream source.

```bash
# Amazon Web Services (JSON)
curl -O https://raw.githubusercontent.com/jonhadfield/cloud-ips/main/aws.json

# Cloudflare (JSON)
curl -O https://raw.githubusercontent.com/jonhadfield/cloud-ips/main/cloudflare.json

# Tor exit nodes (plain text)
curl -O https://raw.githubusercontent.com/jonhadfield/cloud-ips/main/tor.txt
```

To fetch or refresh these lists yourself, use
[ip-fetcher](https://github.com/jonhadfield/ip-fetcher):

```bash
go install github.com/jonhadfield/ip-fetcher/cmd/ip-fetcher@latest
ip-fetcher aws --stdout
```

## License

This project is licensed under the [Apache-2.0](LICENSE) License.

## Acknowledgments

Generated by [ip-fetcher](https://github.com/jonhadfield/ip-fetcher).
