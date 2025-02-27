---
layout: post
title:  "MyBitcoin"
date:   2011-08-05 11:52:03 -0700
categories:
- application_vulnerability
link: http://archive.is/LUMzs
---
This sounds like an application vulnerability that allowed forged deposits that could eventually be withdrawn from a hot wallet. This sort of attack is more common with "off blockchain" ledgers.

>After careful analysis of the intrusion we have concluded that the software that waited for Bitcoin confirmations was far too lenient. An unknown attacker was able to forge Bitcoin deposits via the Shopping Cart Interface (SCI) and withdraw confirmed/older Bitcoins. This led to a slow trickle of theft that went unnoticed for a few days. Luckily, we do keep a percentage of the holdings in cold storage so the attackers didn’t completely clean us out. Just to clarify, we weren’t “fully” hacked aka “rooted”. You can still trust our PGP, SSL, and Tor public keys.
