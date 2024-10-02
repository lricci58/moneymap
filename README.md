# Money Map

A tool to keep track of my personal finances. It includes tracking for income/spending, 
investment, credit card usage, crypto, and other transactional movements. It also has 
an investment simulator, to help you know what you can buy with a specific amount of 
money.

## Table of contents
- [Why I Created This](#why-i-created-this)
- [Features](#features)
- [Current State](#current-state)
- [Deployment](#deployment)
- [License](#the-license)

## Why I Created This

I started using Google Sheets for this project to keep track of my finance —income, spending, debt, etc. 
I slowly started automating things with formulas. Then I discovered AppScript and even managed to scrape 
webpages for real-time share prices. It was working like a charm!
But after a while, I realized I created a Frankenstein monster of features that could totally be streamlined 
in a web app. -Also, I knew it'd be a cooler and more fun project than just exporting the Sheet as an .xlsx to 
improve the scripts' execution rates.

Now, I have a proper database design using MySQL, HTML, CSS, and JS for a fully customized frontend that just 
makes life easier 🤗, and PHP handling the backend. And let's not forget my close friend VSCode —definitely a 
huge upgrade from the clunky AppScript editor.

## Features

This project features the following:
- Fiat and crypto movement tracking (including income, spending and transactions).
- Statement generator (monthly, yearly and of custom range).
- Investment tracking (only Argentinians CDs for now, aka CEDEARs)
- Share-Data scraping using YahooFinance.

**Remember that you can find a sample of the webapp with fake data [here](https://google.com).**

For the future, I plan on adding the following:
- Investment tracking for other currencies and share-types.
- Credit card payment (and debt) tracking.

## Current State

This is still on its alpha version. It's not even close to finished and most importantly, 
it's only for private use for now. You require the use of your own database and server 
(both  of which you can host locally or remotely). I do it locally, since I use this system 
on PC only.

Note. Although I would like to make a service out of this, I don't count with the necessary 
infrastructure to do so yet, and since I wouldn't trust such important information on a 
third-party server for storage, the possibility of it happening it's still a dream...

## Deployment

Not possible for now. Although I guess you could reverse engineer the database with what you 
can see  in this github project and complete/change things to meet your needs. This whole code 
is of public domain after all... You only need a connection file, and the server, which can be
run locally like I do it.

## License
#### The Unlicense / PUBLIC DOMAIN

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to [http://unlicense.org](http://unlicense.org)