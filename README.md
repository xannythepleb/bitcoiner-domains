# Bitcoiner Domains
Regex domain lists for the Pi Hole, AdGuard Home, and anything else accepting regex. Whitelists to allow wallet, node, and Nostr domains etc.

Will be expanded over time, hopefully to also include a blocklist for scams targeting Bitcoiners too.

# Why?

Many common blocklists for Pi Hole, AdGuard Home, and other DNS based blocking systems, especially (but not only) the large ones targeting malware, often broadly block all nodes, wallets, mining pools, and so on, regardless of legitimacy, out of an abundance of caution in an attempt to prevent cryptojacking. While this is a real threat, blocking legitimate sites such as Bitcoin wallets does not protect anyone - it is at best security theatre, at worst actively pushing people away from legitimate sources and onto shady ones.

I first noticed how significant this issue was when trying to use my Lightning node after setting up AdGuard Home on my Pi. I began adding custom unblock rules and decided to share them with the community and open them up to PRs.

Hence, this repo was born.

# How to use

Simply add the following URL to your allow list:

`https://raw.githubusercontent.com/xannythepleb/bitcoiner-domains/main/Bitcoiner-whitelist`
