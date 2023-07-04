# discord-automod
Discord AutoMod is a system of multiple content filters designed to make content moderation easier and less work for moderators. AutoMod lets you filter messages based on regular expression (regex) patterns in your Custom Keyword rules. This repository is a collection of regular expression patterns for your AutoMod rules.

# What are regular expressions?
Regular expressions, or regex, are an advanced form of string pattern matching. They provide a powerful, flexible, and efficient way to detect patterns in large amounts of text.

# How it works with AutoMod
Using a Custom Keywords Rule in AutoMod, you can build a list of keywords and terms to filter. For additional flexibility, you can use regular expressions to define patterns that AutoMod will detect in messages and respond to based on your rules.

Think of a regex pattern as a group of keywords packed together. Since regex filters based on patterns instead of individual keywords, they become a more efficient way to filter messages. Since they're based on patterns, regular expressions are an effective way to prevent people from trying to intentionally bypass your filters by misspelling words or using common variants. They also allow rules that block messages containing phone numbers, email addresses, mailing addresses, or even zalgo text.

AutoMod uses the Rust flavor of regex. To edit and test your regex patterns, you can use one of the following sites:
* [Rustexp](https://rustexp.lpil.uk/)
* [Regex101](https://regex101.com/) (Be sure to select "Rust" as the flavor.)

# More information
* [Filter Messages Using Regular Expressions (Regex)](https://support.discord.com/hc/en-us/articles/10069840290711)
* [AutoMod FAQ](https://support.discord.com/hc/en-us/articles/4421269296535-AutoMod-FAQ)
* [DMA XXX: Regex for Discord Automod 101](https://docs.google.com/document/d/1RtuVwBqALSbRP8xt2RhcZ8J9FXnEHOa-RfXcg9yX2T4/edit?pli=1)
