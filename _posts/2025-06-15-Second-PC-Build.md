---
layout: post
title: "No compromises AM5 PC build in 2025"

tags: ["PC Build"]
categories: ["PC", "Build"]

description: "My second (and most recent) PC build. Designed to fix problems with the original build"
---



## Foreword
---
This is my second (and most recent) PC build. The parts list is very similar to the [original build](_posts/2025-01-30-First-PC-Build.md)
However, there are some changes which will be described later on.

**This post is still being updated with images**

**ALL money is measured in USD**

> **DISCLAIMER:** As the market has changed dramatically since this build was completed, I do NOT suggest replicating it 1 to 1. **Many** changes are needed to achieve a similar price-performance ratio in the modern market.

## Parts list and budget
---
My budget for this PC was a total of $900-1000, which was enough for a decent lower-middle range build.


| Part | Item | Cost | Note |
|------|------|------|------|
| CPU | AMD Ryzen 5 7600X | - | Bought in mobo-cpu-ram bundle |
| RAM | G.Skill Flare X5 16GB DDR5 @ 6000 | - | Bought in mobo-cpu-ram bundle |
| RAM (additional) | G.Skill Flare X5 16GB DDR5 @ 6000 | $49.98 | Additional RAM; matches exactly with the bundled RAM |
| Motherboard | ASUS B650-A AX II | - | Chosen for mATX form factor, expandable RAM, and built-in WiFi |
| CPU + RAM + MOBO Bundle | - | $279.99 | Includes CPU, RAM, and motherboard listed above |
| Storage (boot drive only) | WD SN5000 500GB | $44.99 | No additional storage included |
| CPU Cooler | Cooler Master Hyper 212 CPU Air Cooler (Black, **NO** RGB) | $29.99 | Same as in my first PC build. No trouble cooling under normal load. Quiet and efficient |
| GPU | AMD Radeon RX 9060XT 16GB | $389.99 | Bought only a few days after release |
| Power Supply | Thermaltake Smart Series 700W 80 Plus ATX | $59.99 | Cost-effective without being dangerously cheap |
| Case | Thermaltake Versa H18 | $54.99 | MicroATX form factor; clean and budget-friendly |
| Extra Case Fans + PWM Splitters | be quiet! PURE WINGS 3 120mm + Fan Splitters | $29.97 | Slightly louder than preferred at high speeds; less noticeable while gaming |
| Total | - | $939.89 | Does not include tax; price at time of purchase |

> Costs above do not include tax and represent costs at my time of purchase. Due to market changes, this same build would be about $1450
{: .prompt-tip}


## Overview
---
My goal for this build was to fix all of the problems with my first PC build. Looking back, I feel that I have accomplished that and more. The most apparent problem with my first build was the outdated, low end GPU paired up with a current-gen CPU (Ryzen 5 7600X).

### CPU & Cooler
The CPU is the exact same as the one used in the first build, the Ryzen 7600X from AMD. It is extremely fast, a very popular choice for AM5 PCs and fit my budget perfectly.

It's cooled it with the Cooler Master Hyper 212; the same one used in the initial build, just without RGB. I was going for an all-black aesthetic with this build, focusing on keeping it minimal and clean.

### GPU
While I kept the same CPU, I upgraded the GPU significantly to a Radeon RX 9060XT for a performance gain (comparing only the GPUs) of about +250%. [**Source**](https://gpu.userbenchmark.com/Compare/AMD-RX-9060-XT-vs-AMD-RX-570/m2417253vs3924){:target="_blank"}

> Theoretically, this should increase overall performance by 2.5x, a huge improvement.
{: .prompt-tip}

I bought this GPU just days after it was available at my nearest MicroCenter. I bought it at just a little bit above MSRP ($349) at launch for $390.

### RAM
The quantity of RAM for both builds was the same, but the clock speed is the main difference. RAM's clock speed refers to how fast it can send and receive data to and from the CPU. The original build has 32GB DDR5@5600MHZ, while the new build has 32GB DDR5@6000MHZ. This should give a performance boost of roughly +50% (only comparing RAM).

The RAM speed is limited to 4800MHZ to prolong its lifespan. This was done automatically in the UEFI (BIOS), and could be changed to allow the full speed of the RAM through AMD EXPO or Intel XMP.
> The market has shifted drastically, especially with RAM due to the RAM shortage. This is the main reason that this build is significantly less viable.
{: .prompt-tip}

### Motherboard
In this PC is the ASUS B650-A AX II motherboard. It is a micro ATX form factor but has most of the features of a full ATX. There are 4 RAM slots, although I only have 2 filled right now and 4 PCIE x16 slots, one of which is covered by the GPU.


### Powersupply (PSU)
Powersupplies usually function at peak efficiency at about 40-60% of their max power draw. This PC has a total estimated power draw of 390-425 watts[^fn1] (according to [pcpartpicker](https://pcpartpicker.com/list/fZPWGk)). I chose the same type as PSU as in the last PC; a 700 watt Thermaltake PSU. It is budget friendly, and decent efficiency (80 plus silver). It also gives some headroom to upgrade any component within a reasonable range.



### Case & Fans
I wanted to keep with the minimal look and feel of this build, while not spending a fortune on a case. 
> The price of a case can be astronomically high just because it has one small feature or a big brand name.
{: .prompt-tip}

The Thermaltake Versa H18 was perfect for me because it is one of the cheapest cases on the market that is still more than functional and looks amazing.
It came with one case fan (used as the rear exhaust fan) and I purchased 2 extra 'be quiet' 120mm case fans as an add on for intake. They are a little bit loud and i notice them when no audio is playing from the PC or when I am zoning out from what I'm working on.

### Storage
Initially, I had a 500GB WD-Blue M.2 SSD on hand, which I used as my boot drive and where I originally installed my games. As storage got tighter and I obtained a 1TB 3.5" SATA HDD from one of my older computers, installed it into my system and moved all games to that drive. Since then, I have added another 1TB 2.5" SATA SSD drive, for my games with annoyingly long load times or for games that need to load faster (esports and competitive games).

Compared to the original PC's total of 1TB SATA SSD storage, my 2.5TB is enough to comfortably fit many games, apps and large files with lots of room to add more later[^fn2].

## Summary/Performance results
---

Overall, this PC has a passmark rating of 10,957, coming in at 81st percentile.

Broken in to categories, it had (rounded to neared whole number):
  - 29230   CPU Score
  - 1363    2D Graphics Score
  - 20092   3D Graphics Score
  - 3363    Memory Score
  - 19253   Disk Score
<br>
<br>

The old PC had an overall passmark rating of 3163.8, or 33rd percentile.

Broken into categories, it had:
  - 25944 CPU Score
  - 990   2D Graphics Score
  - 7906  3D Graphics Score
  - 3238  Memory Score
  - 2625  Disk Score

You can view the full parts list [here](https://pcpartpicker.com/list/vxwv6B){:target="_blank"} (includes all extra storage drives, for the build with no extra drives, click [here](https://pcpartpicker.com/list/ktq2FP){:target="_blank"})

To conclude, the new PC performs about %% better in benchmarking than the old PC, likely due to faster memory clocks, MUCH better GPU, and much better storage.

I am happy with the results of this PC, it performs pretty much every task that I have used it for (gaming, rendering, modeling and many more) with absolutely no issues. In the coming days, I will be benchmarking some popular games and posting the results here.

## Future Upgrades
---

Currently, I am very happy with this build. I have no motivation to upgrade any parts, but I do know that eventually I will want to.

### CPU
The 7600X provides more than enough power for my current use cases. I do not plan on upgrading but I do have a couple suggestions for others.

#### 1. Ryzen 7 7800X3D

While it carries a significantly higher price, it is the slightly more powerful in gaming that the 7600X. The 7800X3D has 8 cores and 16 threads (up from 6 cores and 12 threads), allowing for heavier multitasking and more background apps. Some technical stats & numbers can be viewed [here](https://www.cpubenchmark.net/compare/5036vs5033vs5299/AMD-Ryzen-7-7700X-vs-AMD-Ryzen-5-7600X-vs-AMD-Ryzen-7-7800X3D){:target="_blank"}, on the Passmark website. I do not see myself making this upgrade anywhere in the near future but for those with some extra budget and who want some extra power, the 7800X3D could be a better choice.

#### 2. Ryzen 7 7700X

This is the Ryzen 7 equivalent to the 7600X. It serves as the next 'step' up in the line, carrying 8 cores and 16 threads at a base clock speed of 4.5GHz (compared to the 7600X's 4.7GHz and the 7800X3D's 4.2Ghz). [Passmark comparison](https://www.cpubenchmark.net/compare/5036vs5033vs5299/AMD-Ryzen-7-7700X-vs-AMD-Ryzen-5-7600X-vs-AMD-Ryzen-7-7800X3D){:target=":_blank"}

### RAM
Due to the current RAM shortage, I don't see myself replacing or upgrading my RAM anytime soon. These suggestions assume that the RAM shortage's inflated prices aren't a problem and will be based off pre-shortage price/performance values. 

#### 1. 64GB Upgrade (4x16 same RAM @ 6000MHZ)

This is the simplest upgrade, but carries a lot of value, IF you have a use for it. Essentially speaking, RAM that is never utilized is wasted budget that could be better spent on 
other parts. I personally think 32GB is the sweet spot for gaming but for those who run games at higher resolutions or use more detailed textures, effects or other settings in-game or for other apps, 64GB may be the better choice.

#### 2. Memory Speed Upgrade (2x16 same RAM @ >6000MHZ)

Memory's speed is affected by more than just its refresh speed. There are 2 other main aspects of memory speed; latency and timing.
The refresh speed refers to the memory bandwidth, or "how much data can be transferred within a given time period." (HP "Does RAM Speed Matter?", hp.com)
Latency is the amount of time between a command being entered and the start of data transfer and timing is a set of (4) numbers that describes various delays in the RAM (also called CAS timings).

RAM speeds impact many aspects of a computer, including:
  - Faster data transfer rate between CPU, increasing system responsiveness
  - Quicker application load times
  - Better multitasking efficiency
  - Higher grade of CPU performance
  - Better game performance, especially in large, open worlds or complex AI systems. It also helps keep more consistent frame rates, keeping 1% lows closer to the average.

For this upgrade, any higher bandwidth will be an improvement, but be sure to check latency and CAS timings and refer to a chart like [this one](https://www.reddit.com/media?url=https%3A%2F%2Fi.redd.it%2F7bvnt0ohigwd1.jpeg){:target="_blank"}

### Storage
I know that sooner or later I will need even more storage and eventually my drives will start to fail and need to be replaced. When this inevitably happens, I plan to keep adding SATA SSDs for storage as they are fast *enough* for me. When my HDD starts failing, I will replace is with a SATA SSD as well. For my boot drive, I plan to upgrade it to a 1 or 2 TB M.2 SSD of whatever the current generation will be when the time comes.


## Work Cited[^fn3]
- Pre-existing knowledge
- [HP - Does RAM Speed Matter?](https://www.hp.com/us-en/shop/tech-takes/does-ram-speed-matter){:target="_blank"}
- [CPUbenchmark](https://www.cpubenchmark.net){:target="_blank"}
- [UserBenchmark](https://userbenchmark.com){:target="_blank"}
- [PC Part Picker](https://pcpartpicker.com){:target="_blank"}
- [Reddit - Is the Ryzen 5 9600X worth the $40 premium over the 7600X](https://www.reddit.com/r/buildapc/comments/1gbve44/is_the_ryzen_5_9600x_worth_the_40_premium_over/){:target="_blank"}
- [Reddit - What CPU should I upgrade from my 7600X](https://www.reddit.com/r/ryzen/comments/1d795jy/what_cpu_should_i_upgrade_from_my_7600x/){:target="_blank"}
- [Reddit - Ryzen 5 7600X vs Ryzen 7 7800X3D](https://www.reddit.com/r/buildapc/comments/18pug79/ryzen_5_7600x_vs_ryzen_7_7800x3d/){:target="_blank"}

---
#### Notes
[^fn1]: This number is a range of the build with all drives installed and only the boot drive installed
[^fn2]: The Versa H18 case has internal space for up to two 2.5" drives and two 3.5" drives
[^fn3]: All Reddit posts fact checked and cross referenced
