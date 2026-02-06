# irishLists

A collection of Irish-specific word lists and domain name datasets.

## Word Lists

| File | Description | Format | Source |
|------|-------------|--------|--------|
| irish_firstnames.csv | Most common registered Irish first names (male & female), 1964-2016 | name, count, domain | Central Statistics Office |
| irish_counties_domainnames.csv | All 32 Irish counties as .ie domains | domain | |
| words_ending_in_ie_by_popularity.csv | Words ending in "ie" ordered by popularity with corresponding .ie domains | word, domainname | |

## Domain Lists

| File | Description | Format | Source |
|------|-------------|--------|--------|
| ie_domains_from_cisco_umbrella_by_popularity.csv | Popular .ie domains by DNS traffic | rank, domain | Cisco Umbrella |
| ie_domains_magestic_millions_dec_2019.csv | .ie domains ranked by link profiles (Dec 2019) | GlobalRank, TldRank, Domain, etc. | [Majestic Million](https://blog.majestic.com/development/majestic-million-csv-daily/) |
| ie_domains_from_words.csv | .ie domains generated from words ending in "ie" (381 domains) | domain | Derived from words_ending_in_ie_by_popularity.csv |
