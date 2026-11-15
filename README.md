# dmit vs bandwagonhost: which is cheaper in Los Angeles, Hong Kong and Tokyo, who serves China Unicom and China Mobile better, and what the refund rules actually allow

On November 3, 2026, BandwagonHost was the cheaper way into Los Angeles CN2 GIA. Its E-Commerce 40G cost $89.99 per three months, roughly $30 a month, against $79.90 a month for the cheapest DMIT Los Angeles Pro plan that could actually be ordered that day. In Hong Kong the order flips: DMIT's HKG.AS3.Pro.TINY was $39.90 a month against $89.99 at BandwagonHost. In Tokyo, only BandwagonHost had anything in stock.

Those three numbers settle most of the question before anyone starts arguing about route quality. What the price tags don't show is which carrier each route serves in which direction, what happens when the monthly transfer runs out, how long you have to get your money back, and two policy details that rule one of the two out for certain buyers.

Prices, stock and policy terms below were taken from both stores' order pages on November 3, 2026. Neither store was running a sale that day.

## Quick picks

- **Serving China Telecom visitors from Los Angeles on a small budget:** BandwagonHost E-Commerce 40G, $89.99 per 3 months, 3 cores, 2 GB RAM, 40 GB SSD, 2 TB a month at 2.5 Gbit/s. It cannot be paid monthly.
- **Serving China Unicom or China Mobile visitors from Los Angeles:** BandwagonHost's DC9 plans, or DMIT's EB line when it is in stock. It wasn't on November 3. DMIT's own support tells Unicom and Mobile users to take EB, so this is not a guess.
- **Serving Hong Kong or southern China and want the lowest entry price:** DMIT HKG.AS3.Pro.TINY, $39.90 a month for 1 vCPU, 1 GB RAM, 20 GB SSD and 500 GB at 1 Gbit/s.
- **Need Tokyo this week:** BandwagonHost at $89.99 a month. Every DMIT Tokyo Pro plan was out of stock.

👉 [See which DMIT Pro plans are in stock and what they cost today](https://www.dmit.io/aff.php?aff=9081)

## Every DMIT plan on the store, with the stock status from the same day

| Plan | Specs | Price | Stock, Nov 3 2026 | Order |
| --- | --- | --- | --- | --- |
| LAX.AN5.Pro.MINI | 4 vCPU / 4 GB / 80 GB SSD; 5,000 GB at 10 Gbit/s | $79.90/mo; $239.90/3 mo; $479.40/6 mo; $939.90/yr | In stock | [ Order LAX.AN5.Pro.MINI](https://www.dmit.io/aff.php?aff=9081) |
| LAX.AN5.Pro.MICRO | AN5 tier above the MINI; spec sheet on the order page | $110.90/mo | In stock | [ Order LAX.AN5.Pro.MICRO](https://www.dmit.io/aff.php?aff=9081) |
| LAX.AN4.Pro.MINI | AN4 (EPYC 9004) tier | $72.90/mo | Out of stock | [ Check LAX.AN4.Pro.MINI](https://www.dmit.io/aff.php?aff=9081) |
| LAX.AS3.Pro.TINY | 2 GB RAM; 1,000 GB at 1 Gbit/s | $10.90/mo | Suspended, no stock | [ Check LAX.AS3.Pro.TINY](https://www.dmit.io/aff.php?aff=9081) |
| HKG.AS3.Pro.TINY | 1 vCPU / 1 GB / 20 GB; 500 GB at 1 Gbit/s | $39.90/mo; $119.70/3 mo; $239.40/6 mo; $478.80/yr | In stock | [ Order HKG.AS3.Pro.TINY](https://www.dmit.io/aff.php?aff=9081) |
| HKG.AS3.Pro.STARTER | 1 vCPU / 2 GB / 40 GB; 1,000 GB at 1 Gbit/s | $79.90/mo | In stock | [ Order HKG.AS3.Pro.STARTER](https://www.dmit.io/aff.php?aff=9081) |
| TYO.AS3.Pro.TINY | 1 GB RAM; 500 GB at 1 Gbit/s | $21.90/mo | Out of stock | [ Check TYO.AS3.Pro.TINY](https://www.dmit.io/aff.php?aff=9081) |
| HKG.AS3.EB.WEE | Eyeball entry plan; Hong Kong EB is in beta | Monthly billing, or $74.70/3 mo | Listed, beta | [ Check HKG.AS3.EB.WEE](https://www.dmit.io/aff.php?aff=9081) |

Three things about that table matter as much as the prices.

The store, not the pricing page, is the accurate stock source. On November 3 DMIT's pricing page still displayed "Order Now" buttons for the Los Angeles AS3 Pro and every Tokyo Pro plan while the store marked them out of stock. The pricing page itself carries a note that its table "may not be updated in time". Old guides quoting DMIT Los Angeles Pro at under $20 a month are pointing at plans that either no longer exist or cannot be ordered; the smallest Los Angeles Pro that could be bought on November 3 was $79.90 a month.

The hardware codes are generations. AS3 is EPYC 7003, AN4 is EPYC 9004, AN5 is EPYC 9005. DMIT's own pricing page warns that the LAX AS3 series "is still being built out and optimized", with possible reduced disk performance and a lower SLA. The cheap AS3 plans are not the ones to put a production site on.

T1 plans carry no China optimization at all. They are listed at $36.90 a year for T1.WEE, $6.90 a month or $76.90 a year for T1.TINY, $12.90 a month or $262.80 a year for T1.MINI, and $49.90 a month for T1.MEDIUM, and on November 3 only the Hong Kong T1 plans were in stock. If your visitors are in China, T1 is the wrong product line regardless of price.

## The Los Angeles comparison that actually matters: $56.99 against $79.90

Match the two on 4 cores, 4 GB RAM and 80 GB of storage and the gap is $22.91 a month. BandwagonHost's 80G plan costs $56.99 a month, or $549.99 a year, with 3 TB of transfer at 2.5 Gbit/s. DMIT's LAX.AN5.Pro.MINI costs $79.90 a month with 5,000 GB at 10 Gbit/s.

The extra $23 buys transfer volume and port speed. It does not buy a better line, because both are selling China Telecom CN2 GIA into the same city. A single small site serving Telecom visitors will not come close to 3 TB, and 2.5 Gbit/s is far more than a text-and-images site can use. In that case the cheaper plan is the correct purchase and the upgrade is money spent on a ceiling you never reach.

Pay the $79.90 when transfer or port is your actual bottleneck: video, large downloads, a proxy serving several people, or anything that would notice a 10 Gbit/s port. It is also the only way to buy DMIT in Los Angeles month to month right now, since the cheap AS3 tiers are suspended.

BandwagonHost's monthly billing floor in Los Angeles is worth knowing before you plan a short project. The $89.99 40G quarter cannot be paid monthly. The cheapest plan it will bill monthly is the 80G at $56.99. DMIT will bill every Pro and EB plan monthly. For a one-month test that works out to $56.99 at BandwagonHost versus $79.90 at DMIT, so monthly flexibility does not make DMIT cheaper in Los Angeles; it only means you are not committing to a quarter.

👉 [Compare DMIT's in-stock Los Angeles and Hong Kong Pro plans](https://www.dmit.io/aff.php?aff=9081)

## Routes, carrier by carrier and direction by direction

| Location | China Telecom | China Unicom | China Mobile |
| --- | --- | --- | --- |
| Los Angeles, DMIT Pro | CN2 GIA, both directions | Unicom Premium, inbound only | CMIN2, inbound only |
| Los Angeles, BandwagonHost DC9 | CN2 GIA, China-bound | Unicom Premium, China-bound | CMIN2, China-bound |
| Hong Kong, DMIT Pro | CN2 GIA, both directions | No Unicom route listed | CMI, inbound |
| Hong Kong, BandwagonHost | "Direct route via China Telecom (CN2 GIA), China Unicom, China Mobile" | Same | Same |
| Tokyo, DMIT Pro | CN2 GIA, both directions | No Unicom route listed | CMI, inbound |
| Tokyo, BandwagonHost | Same as Hong Kong, plus "CN2 GIA preference on outbound" | Same | Same |

Read the direction column carefully, because the two vendors use different words for the same thing. DMIT's February 2026 Telegram note defines inbound as traffic from China Unicom to the DMIT server, meaning China to server, and outbound as the server's return path to China. BandwagonHost's "China-bound" is that same return path.

In Los Angeles this produces a real difference for Unicom and Mobile visitors. BandwagonHost says all China-bound traffic on DC9 goes out over three carriers: CN2 GIA, China Unicom Premium and CMIN2. DMIT's Los Angeles Pro lists CN2 GIA in both directions, but Unicom Premium and CMIN2 only for traffic coming in. A DMIT support reply quoted by a tester puts it plainly: "The telecom network recommends LAX Pro network, and the Unicom and Mobile networks recommend LAX EB network." EB is the line DMIT built for exactly that job, and on November 3 every Los Angeles EB plan was out of stock.

Vendor route tables are marketing until a traceroute agrees with them. Third-party tests posted to NodeSeek in August and September 2026 found BandwagonHost's DC9 sending traffic back to Unicom over the premium networks in most cases, while DC6 returned to Unicom in Shanghai, Guangzhou and Chengdu over either CN2 GIA or ordinary 4837 rather than Unicom Premium. On the DMIT side, a September 26, 2026 trace back to Tianjin Unicom ran on CN2 GIA and then switched to Unicom 4837 in Beijing, while EB stayed on Unicom's own network the whole way. If Unicom latency is the thing you are buying, test your own city after ordering, inside the refund window.

## The fine print that changes the decision

### When the monthly transfer runs out

BandwagonHost suspends the VPS until the end of the month and charges no overage; upgrading the plan restores it early. DMIT throttles Los Angeles plans instead, at the speed listed on the plan: the MINI runs "Unmetered @ 8Mbps" after its 5,000 GB, and the smaller AS3 tiers drop to 4 Mbit/s. Hong Kong and Tokyo plans pause until the monthly reset. A paid reset on most DMIT plans costs one month's fee.

For a live site, a throttled server that still answers is worth more than a suspended one. For a batch job that must finish, neither is much help, and the paid reset price is the number to budget for.

### An IPv4 fee starts on December 1, 2026

DMIT will charge $1 a month for each IPv4 address in its older Cogent range, the ones starting with 154, that a customer keeps. Moving to a DMIT-owned address is free. If you are on an old DMIT IP, that is a small bill arriving next month; if you are buying now, confirm which range you get.

### The refund windows are shaped differently

BandwagonHost refunds new orders within 30 days if you have used under 10% of the monthly transfer and no IP has been blacklisted. The refund goes back to the original payment method only, and once it is issued every service on the account is terminated and the data deleted.

DMIT gives a full refund within 3 days and 30 GB of use. Partial refunds run to 30 days, calculated on unused time or unused transfer, whichever is less. You can take it as account credit with no fee or back to the original payment method minus the processor's fee. Renewal invoices are not refundable, and an invoice paid with account credit can only be refunded to credit. DMIT also states it will not refund to your payment method because "The network is not good enough".

Buyers who want two or three weeks to judge a route need BandwagonHost's window, and need to keep usage under 10% while testing. Buyers who are confident about the plan and only need a short sanity check can use DMIT's 3-day full refund and lose nothing.

### DMIT bans VPN tunnels to China, and that is a hard exclusion

DMIT's acceptable use policy allows an "Encrypted Private Proxy" and bans public proxy services that could get its addresses blocked. It also bans building VPN tunnels to China, naming OpenVPN, L2TP, PPTP, IPSec and Cisco AnyConnect. BandwagonHost bans open proxy servers and Tor relays, has no rule about VPNs, and lists "PPP and VPN support (tun/tap)".

If your workload involves a tunnel to a network inside China, DMIT is out, whatever the route quality looks like.

### IPv6 does not ride CN2 GIA on either service

Both hand out a /64, and neither states that IPv6 traffic uses CN2 GIA. NodeSeek tests from October 2026 show what that means in practice: on a Los Angeles Pro server, IPv4 back to Guangdong Telecom used CN2 GIA, while IPv6 back to Telecom in Shanghai and Guangzhou ran on the ordinary 163 backbone (AS4134) and IPv6 to Beijing went out through Unicom's 9929 and 10099. The same pattern showed up on Hong Kong Pro on October 4 and Tokyo Pro on October 10, where IPv6 to Telecom and Unicom used 163 and Mobile used CMI while IPv4 used CTG GIA for all three. Over IPv6 from a Guangdong Telecom home line, a Cloudflare speed test measured 71.5 Mbit/s down and 3.45 Mbit/s up; the tester's advice was for Telecom users to stay on IPv4.

No 2026 test of BandwagonHost's IPv6 routes to China turned up, so there is nothing to compare. If IPv6 is part of your plan for Chinese visitors, neither vendor has a documented China-optimized v6 path, and you should design around IPv4.

## Hong Kong and Tokyo are separate decisions

Hong Kong is where DMIT's pricing is hard to argue with. $39.90 a month against $89.99, both with 500 GB at 1 Gbit/s. The catch is the hardware: DMIT gives 1 vCPU, 1 GB RAM and 20 GB SSD at that price, while BandwagonHost gives 2 cores, 2 GB and 40 GB. You are paying 2.25x at BandwagonHost for roughly double the machine. A NodeSeek report from October 4, 2026 found Hong Kong Pro sending IPv4 back to all three carriers in Beijing, Shanghai and Guangzhou over CTG GIA, with 9 to 16 ms to Guangdong, 28 to 32 ms to Shanghai and 42 to 80 ms to Beijing. DMIT lists no Unicom route in Hong Kong; BandwagonHost advertises a direct route for all three carriers. Hong Kong EB exists but DMIT labels it beta and says it is "not yet recommended for production workloads that require high stability".

Tokyo is decided by stock. BandwagonHost's 40G at $89.99 a month, 2 cores, 2 GB, 40 GB, 500 GB at 1.2 Gbit/s, was orderable. Every DMIT Tokyo Pro plan was not, including the TYO.AS3.Pro.TINY listed at $21.90.

## What BandwagonHost covers that DMIT doesn't

BandwagonHost sells CN2 GIA in eight locations, adding San Jose, New York, Vancouver, Osaka and Singapore to the three both vendors share, plus Amsterdam on CTGNet. DMIT sells it in Los Angeles, Hong Kong and Tokyo only. BandwagonHost's Osaka and Singapore Ultra plans were $49.99 a month for 2 GB RAM and 500 GB at 1.5 Gbit/s. If your users are in Singapore or on the US East Coast, DMIT has nothing to sell you.

In the three cities where they compete, they sometimes share the same building: Equinix HK2 in Hong Kong and Equinix TY8 in Tokyo for both, with Los Angeles split across CoreSite and Digital Realty facilities.

## FAQ

**Can I pay DMIT monthly?** Yes, every Pro and EB plan. BandwagonHost's $89.99 Los Angeles 40G cannot be paid monthly; its cheapest monthly Los Angeles option is the 80G at $56.99.

**Which is better for China Unicom visitors from Los Angeles?** BandwagonHost DC9 lists Unicom Premium on the China-bound path. DMIT's Pro lists it inbound only and DMIT points Unicom users to EB, which was out of stock on November 3.

**Is DMIT's $10.90 Los Angeles Pro plan available?** No. The order page said it had been "suspended until more stock is available".

**Does either vendor offer CN2 GIA over IPv6?** Neither states it, and October 2026 tests put DMIT's IPv6 return to Telecom on the 163 backbone.

## Final rules

- Telecom-only audience from Los Angeles, tight budget: BandwagonHost 40G quarter at $89.99.
- Unicom or Mobile audience from Los Angeles: BandwagonHost DC9 now, or DMIT EB if you can wait for restock.
- Hong Kong audience, lowest entry price: DMIT HKG.AS3.Pro.TINY at $39.90 a month, accepting 1 GB RAM.
- Anyone who needs a tunnel to a network in China: BandwagonHost, since DMIT's policy prohibits it.
- Anyone who wants weeks to judge the route: BandwagonHost's 30-day window, keeping usage under 10%.
- One box that needs 5,000 GB or a 10 Gbit/s port: DMIT LAX.AN5.Pro.MINI at $79.90 a month.

Two checks before you pay. Confirm stock on the order page rather than DMIT's pricing table, which lags behind. And read the refund clause for the exact plan, since a 3-day full refund and a 30-day partial refund are different safety nets.

👉 [Check DMIT stock and current pricing before you order](https://www.dmit.io/aff.php?aff=9081)
