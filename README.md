# Bitcoiner Domains
Regex domain lists for the Pi Hole, AdGuard Home, and anything else accepting regex. Whitelists to allow wallet, node, and Nostr domains etc.

Will be expanded over time, hopefully to also include a blocklist for scams targeting Bitcoiners too.

# Why?

Many common blocklists for Pi Hole and similar, especially the ones targeting malware, often broadly include any nodes, wallets, mining pools, and so on, regardless of legitimacy.

I first noticed this when trying to use my Lightning node after setting up such a system. I began adding custom unblock rules and decided to share them with the community.

Hence, this repo was born.

# How to use

Simply add the following URL to your allow list:

`https://raw.githubusercontent.com/xannythepleb/bitcoiner-domains/main/Bitcoiner-whitelist`
