# Link database for year 2025

This repository contains link metadata: title, description, publish date, etc.

## Suite of projects

 - Captured using Django application: [https://github.com/rumca-js/Django-link-archive](https://github.com/rumca-js/Django-link-archive)
 - Bookmarked links [https://github.com/rumca-js/RSS-Link-Database](https://github.com/rumca-js/RSS-Link-Database)
 - daily RSS Git repository for the year 2025 [https://github.com/rumca-js/RSS-Link-Database-2026](https://github.com/rumca-js/RSS-Link-Database-2026)
 - daily RSS Git repository for the year 2025 [https://github.com/rumca-js/RSS-Link-Database-2025](https://github.com/rumca-js/RSS-Link-Database-2025)
 - daily RSS Git repository for the year 2024 [https://github.com/rumca-js/RSS-Link-Database-2024](https://github.com/rumca-js/RSS-Link-Database-2024)
 - daily RSS Git repository for the year 2023 [https://github.com/rumca-js/RSS-Link-Database-2023](https://github.com/rumca-js/RSS-Link-Database-2023)
 - daily RSS Git repository for the year 2022 [https://github.com/rumca-js/RSS-Link-Database-2022](https://github.com/rumca-js/RSS-Link-Database-2022)
 - daily RSS Git repository for the year 2021 [https://github.com/rumca-js/RSS-Link-Database-2021](https://github.com/rumca-js/RSS-Link-Database-2021)
 - daily RSS Git repository for the year 2020 [https://github.com/rumca-js/RSS-Link-Database-2020](https://github.com/rumca-js/RSS-Link-Database-2020)

## Goal

 - Archive purposes
 - Data analysis - possible to verify link rot, etc.

## Inspirations

 - I Tracked Everything I Read on the Internet for a Year [https://www.tdpain.net/blog/a-year-of-reading](https://www.tdpain.net/blog/a-year-of-reading).
 - Automating a Reading List [https://zanshin.net/2022/09/11/automating-a-reading-list/](https://zanshin.net/2022/09/11/automating-a-reading-list/)
 - Google Search Is Dying [https://dkb.io/post/google-search-is-dying](https://dkb.io/post/google-search-is-dying)
 - Luke Smith: Search Engines are Totally Useless Now... [https://www.youtube.com/watch?v=N8P6MTOQlyk](https://www.youtube.com/watch?v=N8P6MTOQlyk)
 - Luke Smith: Remember to Consoom Next Content on YouTube [https://www.youtube.com/watch?v=nI3GVw2JSEI](https://www.youtube.com/watch?v=nI3GVw2JSEI). As a society we provide news instead of building a data base of important information
 - Ryan George What Google Search Is Like In 2022 [https://www.youtube.com/watch?v=NT7_SxJ3oSI](https://www.youtube.com/watch?v=NT7_SxJ3oSI)

# Data

## Daily Data

Are stored in the year directory.

 - data are in %Y\%M\%Y-%M-%D directories, where %Y stands for year, %M for month, %D for day
 - Most links are captured via RSS. Some entries were added manually
 - for each source two files are provided: JSON and markdown
 - markdown file is provided for data preview
 - this repo contains many links captured via automated process. They are here, but that does not mean I endorse them all

## Sources

 - file: sources.json
 - provides information about sources, like title, url, langugage

## Domains

 - file: domains.json
 - provides information about domains, like title, url, langugage

## Data analysis

With these data we can perform further analysis:

 - analysis of links: how many of old links are not any longer valid
 - analysis of RSS source: how often it publishes data
 - analysis of RSS source: what kind of data it produces, is it reliable
 - analysis of RSS source: is it a content farm, does it contain many links outside of the domain?
 - analysis of domains: is the domain correctly configured?
 - analysis of topics: who was the first to report on certain topic
 - analysis of topics: which source uses which words? For example it seems that left leaning sites, and white leaning sites have a different vocublary. There are different kind of words and ideads in. With this file history, you can analyze which sites have which ideas

# Problems, notes

 - This solution does not replace Internet Archive. We do not store all link data
 - Internet Archive (archive.org) is sometimes slow
 - This solution does not replace Google. This would be futile. However Google provides only 31 pages of news (in news filter) and around 10 pages for ordinary search. This is a very small number. It is like looking through keyhole at the Internet
 - You cannot discover new content using Google. For example write 'blog' into search. You will not be able to find new blogs.
 - You cannot discover new content using YouTube. For example write 'trailer' into search. It shows me certain amount of new trailers from time span of 10 days, nothing older, or just a few older titles. I prefer capturing data from a movie trailer channel and continue to use it's data
 - Link rot is real. Many github pages do not work at all. Many pages stop working after significant amount of time
 - I am using raspberry PI at the moment. With it I cannot track all of the sources in the world. Therefore I track only 'well established' sources, or the ones I am really interested in
 - Is the data relevant, or useful for anyone but me?

# Q & A

Q: Why are you using sources like daily mail? This does not make any sense!
A: This project aims to capture time capsule of day, or year. In statistics sometimes it is too late to capture "new" data. For analysis only credible, and reliable sources could be used

# Ending notes

All links belong to us!

