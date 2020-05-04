---
layout: post
title:      "GURPS CLI Book Browser"
date:       2020-05-04 22:59:58 +0000
permalink:  gurps_cli_book_browser
---

I have just completed my GURPS CLI Book Browser gem which allows the user to browse the books put out by Steve Jackson Games for the roleplaying game GURPS in a text based interface. It scrapes it's data from the following website.

http://www.sjgames.com/gurps/books/

The scraping process was by far the most difficult aspect of creating the program, as it turns out the website is not very friendly to scraping. It is scrapable, but it uses very few CSS tags, making it difficult to create code that scrapes exactly what I want, some of the links to the book description pages are inconsistent in various sections of the website, and the book description pages do not have a consistent layout, which made it a bit of a challenge to write code that would scrape the description off of every page successfully. Nevertheless, I think I have designed a gem that works quite well. There are literally hundreds of GURPS books, so I have not been able to test it on every possible book's description, but I have tested quite a few, and it seems to work very well on the ones I have tested. I look forward to your feedback on my gem.

Sean Murphy
filmmakersean@fastmail.net


