# cheap vps usa: What $49.99 a Year Buys You, CN2 GIA vs Regular Routes Explained, and How to Pick the Right Plan

Search "cheap vps usa" and you'll hit two kinds of results: providers advertising $2–8/month, and listicles that never tell you what those prices actually include. The short version: BandwagonHost's 20G KVM PROMO costs **$49.99 per year** — that works out to roughly $4.17/month — for 2 vCPU cores, 1 GB RAM, 20 GB SSD, and 1 TB of monthly traffic. It's one of the few sub-$5/month options that includes free snapshots, free automatic backups, and free migration between data centers. If your traffic involves China, the CN2 GIA-E plan starting at $49.99/quarter is the one worth stretching for, because the route quality is something most budget competitors simply don't offer.

> **Quick pick**
> - General-purpose US VPS on a tight budget → 20G KVM PROMO, $49.99/year, 1 TB traffic, multi-datacenter
> - China-facing sites or services → CN2 GIA-E, $49.99/quarter or $169.99/year, triple-carrier optimized routing
> - Pure price floor elsewhere: BuyVM starts at $2/month (1 vCPU, 512 MB), Cloudnium LA at $2.99/month
>
> 👉 [See the 20G KVM PROMO plan at $49.99/year](https://bandwagonhost.com/cart.php?a=add&pid=44&aff=74518)

## What "cheap" actually means in the US VPS market right now

Cheap splits into two very different categories, and mixing them up is how people end up disappointed.

A price tracker covering 267 US plans from 17 providers (checked October 27) puts the absolute floor at **$2/month** — BuyVM's Slice 512 with 1 vCPU, 512 MB RAM, and 10 GB SSD. Contabo's Cloud VPS 4 at $6.15/month for 4 cores and 8 GB RAM scores highest on raw value. Cloudnium sells LA KVM plans from $2.99/month with NVMe storage and 10 Gbps uplinks. HostFinch starts at $7.99/month with unmetered traffic.

At these prices you're buying generic international bandwidth from a US data center. For hosting a blog, a hobby project, or a staging server reachable from anywhere, that's fine. The trap is assuming the cheapest plan will perform the same from *your* location. A $2.99 VPS in Los Angeles with standard transit can look great from a US speed test and fall apart during evening peak hours if your visitors are in Asia. That's the gap BandwagonHost's higher-priced optimized plans occupy — and it's worth understanding before you compare dollar signs.

## BandwagonHost plans and prices: the full lineup

BandwagonHost (run by Canada-based IT7 Networks, with the in-house KiwiVM control panel) currently sells three main product families. All are KVM virtualization, all are **strictly self-managed** (no hand-holding, no managed support), and all carry a 99.95% uptime guarantee.

**Regular KVM PROMO plans** — standard international routes, choose from multiple data centers, free automatic migration between them:

| Plan | CPU / RAM | SSD | Traffic | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 20G KVM PROMO | 2 cores / 1 GB | 20 GB | 1 TB/mo | $49.99/year | [ Get the 20G KVM PROMO](https://bandwagonhost.com/cart.php?a=add&pid=44&aff=74518) |
| 40G KVM PROMO | 3 cores / 2 GB | 40 GB | 2 TB/mo | $52.99/semi-yr or $99.99/yr | [ View 40G KVM PROMO](https://bit.ly/BandwaGon) |
| 80G KVM PROMO | 4 cores / 4 GB | 80 GB | 3 TB/mo | $19.99/mo, $59.99/qtr, $107.99/semi-yr, $199.99/yr | [ View 80G KVM PROMO](https://bit.ly/BandwaGon) |
| 160G KVM PROMO | 5 cores / 8 GB | 160 GB | 4 TB/mo | $39.99/mo or $399.99/yr | [ View 160G KVM PROMO](https://bit.ly/BandwaGon) |
| 320G KVM PROMO | 6 cores / 16 GB | 320 GB | 5 TB/mo | $79.99/mo or $799.99/yr | [ View 320G KVM PROMO](https://bit.ly/BandwaGon) |
| 480G KVM PROMO | 7 cores / 24 GB | 480 GB | 6 TB/mo | $119.99/mo or $1199.99/yr | [ View 480G KVM PROMO](https://bit.ly/BandwaGon) |

Every plan in this table includes RAID-10 SSD storage, 1 dedicated IPv4 address, a routed /64 IPv6 subnet, free automatic backups, free snapshots, manual ISO installs, instant rDNS updates from the panel, and support for CentOS, Debian, Ubuntu, Rocky Linux, and AlmaLinux. The 160G and larger plans add a secondary private network interface.

**CN2 GIA-E plans (Los Angeles)** — the premium routing tier, where most long-term users end up:

| Plan | CPU / RAM | SSD | Traffic | Port | Price | Order |
| --- | --- | --- | --- | --- | --- | --- |
| GIA-E 1G | 2 cores / 1 GB | 20 GB | 1 TB/mo | 2.5 Gbps | $49.99/qtr or $169.99/yr | [ Check CN2 GIA-E quarterly pricing](https://bandwagonhost.com/cart.php?a=add&pid=87&aff=74518) |
| GIA-E 2G | 3 cores / 2 GB | 40 GB | 2 TB/mo | 2.5 Gbps | $89.99/qtr or $299.99/yr | [ View GIA-E 2G](https://bit.ly/BandwaGon) |
| GIA-E 4G | 4 cores / 4 GB | 80 GB | 3 TB/mo | 2.5 Gbps | $56.99/mo or $549.99/yr | [ View GIA-E 4G](https://bit.ly/BandwaGon) |
| GIA-E 8G | 6 cores / 8 GB | 160 GB | 5 TB/mo | 5 Gbps | $86.99/mo or $879.99/yr | [ View GIA-E 8G](https://bit.ly/BandwaGon) |
| GIA-E 16G | 8 cores / 16 GB | 320 GB | 8 TB/mo | 5 Gbps | $159.99/mo or $1599.99/yr | [ View GIA-E 16G](https://bit.ly/BandwaGon) |
| GIA-E 32G | 10 cores / 32 GB | 640 GB | 10 TB/mo | 10 Gbps | $289.99/mo or $2759.99/yr | [ View GIA-E 32G](https://bit.ly/BandwaGon) |

GIA-E plans can be migrated between more than ten data centers from the control panel without losing data — including DC6 (CN2 GIA-E) and DC9 (CN2 GIA, AMD EPYC hardware with NVMe) in Los Angeles, plus locations in Japan and Europe.

**Singapore CN2 GIA plans** — fixed in Singapore's Equinix SG1 facility, no multi-datacenter migration:

| Plan | CPU / RAM | SSD | Traffic | Port | Price (monthly / yearly) |
| --- | --- | --- | --- | --- | --- |
| SPECIAL 40G | 2 cores / 2 GB | 40 GB | 500 GB/mo | 1.5 Gbps | $49.99 / $499.99 |
| SPECIAL 80G | 4 cores / 4 GB | 80 GB | 1 TB/mo | 1.5 Gbps | $86.99 / $869.99 |
| SPECIAL 160G | 6 cores / 8 GB | 160 GB | 2 TB/mo | 2.5 Gbps | $165.99 / $1665.99 |
| SPECIAL 320G | 8 cores / 16 GB | 320 GB | 4 TB/mo | 2.5 Gbps | $329.99 / $3199.00 |
| SPECIAL 640G | 10 cores / 32 GB | 640 GB | 6 TB/mo | 5 Gbps | $549.99 / $5549.99 |
| SPECIAL 1280G | 12 cores / 64 GB | 1280 GB | 8 TB/mo | 5 Gbps | $1059.99 / $10559.99 |

Notice the trade: the Singapore 40G costs $499.99/year for only 500 GB/month of traffic, while a regular 40G KVM at $99.99/year gets you 2 TB. Singapore is priced for route quality and Southeast Asia proximity, not volume.

## CN2 GIA vs regular routes: why the same specs can cost 3x more

The real difference between these plan families is the network path, and this is the part most comparison posts skip.

A regular KVM plan rides standard international transit. On China-facing routes, that traffic typically mixes with ordinary commercial traffic, and during evening peak hours quality degrades badly — third-party measurements have recorded packet loss above 30% on congested standard routes.

CN2 GIA-E plans route over China Telecom's premium AS4809 backbone (CN2 GIA/CTGNet), with China Mobile traffic on CMIN2 and China Unicom on its premium network — all three carriers optimized simultaneously. BandwagonHost operates eight 10 Gbps CN2 GIA/CTGNet links in Los Angeles across the DC6 and DC9 facilities. For reference, CN2 GIA IP transit trades on the wholesale market at roughly $120 per Mbps, which is why these plans cost more and why genuinely equivalent offerings are rare at budget prices.

The route premium isn't just marketing. A May 2026 independent test of BandwagonHost's Los Angeles e-commerce VPS measured 0% global packet loss and 0.3–2.5 ms local latency inside the data center. One practical detail: after purchase, you can switch data centers from the KiwiVM panel to match your carrier's best route, and snapshots and backups move with you.

If you're serving Southeast Asia rather than East Asia, note that BandwagonHost added a new Singapore SG_8 CN2 GIA facility in May 2026 — for users in southern China, latency to Singapore is often lower than to Japan.

## The real cost math (and the coupon situation nobody explains)

Here's where the published prices need context.

The $49.99/year 20G KVM is billed annually only — there's no monthly option at that price, so your minimum commitment is $49.99 up front. The CN2 GIA-E 1G plan has no monthly billing either; the shortest cycle is quarterly at $49.99. That's actually a useful feature: you can run the premium route for three months for the same cost as a year of the basic plan, then decide.

One caveat on that $4.17/month figure: it's a conversion, not a monthly price. And the renewal price for the 20G KVM PROMO isn't published on the order page — don't assume the promo price repeats forever without checking.

On coupons: BandwagonHost discontinued its standing全场 discount codes in late 2025, announcing the end of regular site-wide coupons. Codes still circulating in the community — BWHCGLUKKB is the most commonly cited one — deliver roughly 6% off and reportedly apply to renewals, per third-party code trackers. On a $49.99 plan that's about $3 in savings. The honest takeaway: chasing coupon codes here moves the needle far less than picking the right plan and billing cycle. Test any code at checkout before counting on it.

Compare that to monthly-billed competitors: Cloudnium's LA-1 at $2.99/month costs $35.88/year with no commitment, and HostFinch's entry plan runs $95.88/year but includes unmetered traffic and free managed setup extras. Annual-only billing is the price of BandwagonHost's low rate.

## Who should skip BandwagonHost entirely

Being straight about the limitations saves everyone time.

The 20G KVM PROMO gives you 1 GB of RAM and 20 GB of disk. That's fine for a personal site, a lightweight proxy, a Git server, or learning Linux. It is not a production database server. If your workload needs 4+ GB of RAM at minimum monthly cost, Contabo's 4-core/8 GB plan at $6.15/month is the stronger raw-value play.

BandwagonHost is strictly self-managed. You get full root access and KiwiVM handles reboots, reinstalls, rDNS, and snapshots, but if "set up a firewall" sounds like a chore, HostFinch includes initial security configuration, OS installation, and free site migration with every plan — that support layer matters more than $2/month of savings for a lot of first-time buyers.

And if you need monthly billing flexibility or pay-as-you-go scaling, the annual-only entry plans are a poor fit; hourly-billed clouds (DigitalOcean, Vultr, and similar) are built for exactly that.

| Provider | Entry price | Config | Billing | Standout trait |
| --- | --- | --- | --- | --- |
| BandwagonHost | $49.99/yr (~$4.17/mo) | 2C / 1 GB / 20 GB / 1 TB | Annual only (entry) | CN2 GIA route options, free DC migration |
| Cloudnium | $2.99/mo | 2C / 2 GB / 20 GB NVMe / 2 TB | Monthly | 10 Gbps uplink, CEPH storage, 5 US locations |
| BuyVM | $2/mo | 1C / 512 MB / 10 GB | Monthly | Lowest verified US price |
| Contabo | $6.15/mo | 4C / 8 GB | Monthly | Best RAM-per-dollar among 267 tracked plans |
| HostFinch | $7.99/mo | 1C / 2 GB / 40 GB / 300 Mbps | Monthly, unmetered | Includes setup help and free migration |

## FAQ

**Is the renewal price the same as the signup price?**
For the 20G KVM PROMO, the renewal price is not published on the order page as of the most recent check, so treat the $49.99 as a first-year figure until confirmed in your cart. Longer-cycle prices shown in the tables above (quarterly, semi-annual, annual) are the current listed rates.

**Can I get a refund if I change my mind?**
Refund terms aren't prominently displayed on the product pages. Some third-party guides cite a 30-day window, but verify the policy shown in your cart before paying rather than assuming it.

**Do I really need CN2 GIA if my visitors aren't in China?**
No. The premium routing only pays off on China and parts of Asia-facing traffic. For a US or European audience, a regular KVM plan or a cheaper monthly competitor serves equally well.

**What control panel do I get?**
KiwiVM, BandwagonHost's in-house panel: start/stop, OS reinstall, emergency console, rDNS, data center migration, snapshots, and API access. It's functional rather than pretty, and it does everything a self-managed user needs.

## The bottom line, by situation

Light personal project, want to pay once a year and forget about it → 20G KVM PROMO at $49.99/year. Serving users in China or need evening-peak stability → CN2 GIA-E quarterly at $49.99 as a trial, annual at $169.99 once you're satisfied. Southeast Asia focus → the Singapore CN2 GIA line, accepting the lower traffic caps. Heavy RAM needs or monthly flexibility → a monthly-billed competitor will serve you better than anything in BandwagonHost's entry tiers.

One last check before you order: confirm your billing cycle and — if you're counting on a discount code — that it actually applies in your cart, since the site no longer honors the old standing coupons.

👉 [Open the BandwagonHost plan lineup and pick your billing cycle](https://bit.ly/BandwaGon)
