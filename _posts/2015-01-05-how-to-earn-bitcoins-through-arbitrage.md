---
title: How to Earn Bitcoin Through Arbitrage
excerpt: Interested in automated bitcoin trading software? In 2013 I developed an arbitrage bot to automatically earn bitcoins in a low-risk way.
image: /images/how-to-earn-bitcoin-through-arbitrage.jpg 
popularPostTitle: How to Use BTCJam AutoInvest
---

![How To Earn Bitcoin Through Arbitrage](/images/how-to-earn-bitcoin-through-arbitrage.jpg "How To Earn Bitcoin Through Arbitrage")
I've never been into day trading or forex trading. It's actually surprising I've done option trading (selling) and that I'm investing in bitcoin. I used to be exclusively in index funds and mutual funds. For those who don't know index and mutual funds are some of the safest way to invest in stocks and they provide correspondingly low rates of return.

However in 2013 I was a bitcoin day trader. I used a strategy called arbitrage and wrote a bot to do it. It was a relatively low risk way to earn a relatively high return.

**Arbitrage is my favorite way to earn bitcoins.** Unfortunately I am not currently involved in arbitrage.

#What is arbitrage?

 [Investopedia's Definition:](http://www.investopedia.com/terms/a/arbitrage.asp)

>DEFINITION OF 'ARBITRAGE'
>
>The simultaneous purchase and sale of an asset in order to profit from a difference in the price. It is a trade that profits by exploiting price differences of identical or similar financial instruments, on different markets or in different forms. Arbitrage exists as a result of market inefficiencies; it provides a mechanism to ensure prices do not deviate substantially from fair value for long periods of time.

Khan Academy has a nice explanation and also covers why **performing arbitrage reduces the opportunity.**

<iframe width="854" height="510" src="//www.youtube.com/embed/AuCH7fHZsZ4" frameborder="0" allowfullscreen></iframe>

With that in mind lets look at some bitcoin markets:

![Bitcoin Exchange Price Differences Create Arbitrage Opportunity](/images/bitcoin-exchange-price-differences-create-arbitrage-opportunity.jpg "Bitcoin Exchange Price Differences Create Arbitrage Opportunity")

Notice there are different prices for bitcoin. Based on our understanding above that means there is opportunity for bitcoin arbitrage right?

Yes, Bitcoin Exchange Price Differences Create Arbitrage Opportunity.

# Sounds Easy

##Why doesn't everyone do it?

Bitcoin Arbitrage sounds easy and if it were then the price differences would vanish because everyone would do it.

Key components for successful arbitrage:

1. **Understanding total cost of entering and exiting a position.** When buying bitcoin there are typically exchange fees (variable) and bank fees (fixed) or wire transfer fees.

2.  **Being able to correctly evaluate an opportunity.** - If bitcoin is selling for $1K on Coinbase and $990 on Circle it looks like there is an arbitrage opportunity. Let's look deeper. Coinbase has a 1% with a 15-cent bank fee. Circle has no fees. This means the price difference will need to be greater than $10.15 for the arbitrage to be profitable.

    To make things more complicated most exchanges have an order book. This means the actual price we pay or sell (fill price) is affected by how many bitcoin we are buying. The price for 1 bitcoin on Coinbase might be $1k, but for 25 bitcoins the price might be $1.1K.

3. **Speed** After determining if our opportunity is profitable, and as you can see from taking into account the order book, we need to execute the trade. Both the determination of profitability and the execution need to happen quickly. Otherwise the market prices can change, losing us money.

4. **Capital** It is important to have both bitcoins and cash in place at both exchange points in roughly equal amounts, or up to the daily limits at each exchange. For example if the Coinbase sell limit is $15K / day ideally one would like to arbitrage the max $15K amount. To do that one would need to have $15K worth of bitcoin sitting at Coinbase. On the other side of the trade $15K will need to be sitting at an exchange. It is also important to understand that dollars move slower than bitcoins and don't move on weekends or bank holidays.

5. **Access** to perform arbitrage one needs access to multiple markets trading equivalent securities. For example Bitstamp and Coinbase both buy and sell bitcoin. Being in different countries generally increases fees and transfer times of moving cash.

6. **Turnover** If one doesn't have enough capital to max out the daily exchange limits it is important to increase the speed dollars can be sold from one exchange and moved to the other exchange. If it takes 3 days to move money from the exchange where the bitcoins are sold for cash to the exchange where cash is used to buy bitcoins then one will need 3x the daily limit to try and max the exchange limit each of the three days the cash is en route.


#How was I successful?

I had some advantages:


1.  **I automated the process.** I'm a software developer. I realized the bitcoin markets moved too fast for me to compare two order books and execute a trade. Even with a spreadsheet doing most of the work it took about a minute or two to evaluate arbitrage profitability.

    Most (all?) bitcoin exchanges have APIs (a way for computers to talk to each other) and I was able to write a piece of software (arbitrage bot) that could analyze and execute arbitrage in less than ten seconds between two markets.

2. **I moved cash fast.** I realized with a 2-3 day ACH transfer time my working capital wasn't going to be enough to max out my limits everyday. I found an out-of-state bank that was able to move cash same day into one of the exchanges I was using due to a special relationship. This meant I could cycle my cash every 24 hours instead of 48-72 hours except for weekends and holidays.

3. **One market had a pricing bug.** I soon realized one of the markets I was using had a pricing bug. Typically the net (after expenses) price differences were a fraction of a percent. In the buggy market, about twice a day the net price difference would be 7%. I instructed my software to wait for those big opportunities and ignore the small opportunities.

4. **Access to different markets in the same country.** I was fortunate that I was able to access two different markets here in the U.S. with different prices. This meant I saved a lot of time and money by not needing to move money overseas or convert it to a different currency.

#Why don't I do it anymore?

With my software doing all the work arbitrage was a dream come true. I could (and did) spend some days at the beach and earn a nice 7% return for the day.

Unfortunately my opportunity quickly dried up. One exchange stopped taking deposits and the other fixed their pricing bug. I began focusing on other ways to earn bitcoin. I haven't looked into arbitrage since 2013.

Also there is no such thing as risk-free. I was aware either of the markets could go bust or getting hacked. Additionally my software could have had bugs in it. Fortunately I'm a decent coder and the software processed over 500 profitable transactions worth around $150,000 over a six-week time period.


#What do you think?

Do you see opportunities for arbitrage? Or do you think there are better ways to [earn bitcoins?](/portfolio/) 

Let me know in the comments!