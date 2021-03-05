---
layout: post
title: "US Tax Law and Cryptocurrency Part 1: The Basics"
date: 2021-03-05 14:03:30 -0000
categories: test
---

<style type="text/css">
.post-thumbnail {
    width: 50%; 
    height: auto;
}
</style>


<img src="https://phil.mk/wp-img/01-thumbnail.jpg" class="post-thumbnail">

This material has been prepared for informational purposes only, and is not intended to provide, and should not be relied on for, tax, legal, investment, or accounting advice. You should consult your own tax, legal, investment, or accounting advisors before engaging in any transaction.

I am a certified public accountant that is based out of New Jersey, and I’m going to attempt to write up an extensive guide covering the interactions of United States tax law and cryptocurrency. To begin, I’ll be covering the very basics, and then move on to more complex topics over the coming days.

The IRS uses the term virtual currency to describe a digital representation of value that is convertible into a 'real' currency. Any cryptocurrency that you have purchased on an exchange would fall under this broad definition. The IRS manages to be fairly straightforward in how they treat cryptocurrency transactions: they are considered property, and follow the same rules that come with the disposition of property.

You dispose of property when you do any of the following:

* Sell property.
* Exchange one property for another property.
* You give property away. This is *generally* a non-taxable event for the giver and recipient. A recipient should know your adjusted basis in the property.

This treatment results in a need to diligently track your cryptocurrency transactions, including the converted value of the cryptocurrency to USD at the time of each taxable transaction that you engage in.

Before we get started, let's take a look at what kind of property cryptocurrency is. To do this, we will take a look at [Publication 544](https://www.irs.gov/publications/p544) and scrolling down to the second section: [Ordinary or Capital Gain or Loss](https://www.irs.gov/publications/p544#idm139755998734656). Scrolling down further, we can see that capital assets are defined as **everything** you own and use for personal purposes, pleasure, or investment. Capital assets are then split off into subcategories, the two largest being **personal-use property** and **investment property**. The main distinction here: investment property is purchased with the intent to sell it at a later time. This distinction is important, as the investment property classification allows your capital losses to be deducted. Note: if you have capital losses in excess of your capital gains in a year, the highest amount of your deduction is $3,000. If you have losses greater than $3,000, you can carry over the excess to future years.

To summarize: cryptocurrency is investment property, which requires recognition of capital gains, but allows recognition of capital losses when it is sold or exchanged.

The first step in understanding the tax consequences of your transactions is to find your [adjusted basis](https://www.irs.gov/publications/p550#en_US_2019_publink100010382). This part is fairly simple: how much did you pay, in USD, to purchase your investment? If you were on Coinbase, and spent $50 on 100\~ XLM and a $1.99 Coinbase fee, then your adjusted basis is simply $50.

&#x200B;

![Calculating the adjusted basis.](https://phil.mk/wp-img/01-adjusted-basis.png)

To summarize: the adjusted basis is the amount paid for your cryptocurrency, including any fees.

The second step in determining any tax consequences of your transactions is: did I create a taxable event? The vast majority of investors will only create taxable events with sales and exchanges.

The treatment of exchanges requiring recognition tends to frustrate many cryptocurrency investors. As all cryptocurrency is considered property, every time you convert one cryptocurrency for another, you have caused a taxable event to take place. This is a nightmare for anyone engaging in large volumes of trading in multiple different currencies.

If you believe that you did create a taxable event, the next question to ask yourself is: what did I receive in this sale, or exchange? This is called the [amount realized](https://www.irs.gov/publications/p550#en_US_2019_publink100010429). In the eyes of the IRS: receiving a toaster for your cryptocurrency, or receiving $60 to purchase a toaster with is the same. The only thing that matters is determining the value of whatever you received, plus any cash that went along with the transaction at the time it happened. If you had to pay a fee for your sale or exchange, that would reduce your amount realized. Let's pretend that you waited for your XLM to appreciate, converted it into $55.06 of Ethereum, and paid a $1.99 transaction fee. Your amount realized comes out to $53.07.

![Calculating the amount realized.](https://phil.mk/wp-img/01-adjusted-basis.png)

To summarize: the amount realized is any cash you received, plus the fair market value of any property received, minus any fees paid.

Our capital gain or loss is finished up with a simple subtraction.

Amount realized - adjusted basis = Gain/(loss)

![Calculating the gain/loss.](https://phil.mk/wp-img/03-gain-loss.png)
Ultimately, the classification of property is a mixed bag, leading some things to be more confusing and cumbersome than they ought to be, but also providing certain tax benefits that may not be able to be taken advantage of otherwise.

Hopefully this high level overview was helpful. Over the next coming days, I plan to write more about the interactions of cryptocurrency and tax. These will include:

* wash sales
* the gifting of cryptocurrency
* the handling of transaction fees during nontaxable events
* some assumptions about how IRS treatment will change as time goes on

If you have any questions, feel free to ask them below. They can relate to the items above or about anything else that is tax related.

This post has been published at [LeoFinance](https://leofinance.io/@phul/us-tax-law-and-cryptocurrency-part-1-the-basics), [my own blog](https://phil.mk/us-tax-law-and-cryptocurrency-part-1-the-basics/), [Medium](https://medium.com/phil-mk/us-tax-law-and-cryptocurrency-part-1-the-basics-e4323cb519ec), [Reddit](https://www.reddit.com/r/CryptoCurrency/comments/lrgq1p/us_tax_law_and_cryptocurrency_part_1_the_basics/), and [Publish0x](https://www.publish0x.com/phil-mk/us-tax-law-and-cryptocurrency-part-1-the-basics-xernegp?a=LDdwjJqzb1).

Part 2 is now up on [LeoFinance](https://leofinance.io/@phul/us-tax-law-and-cryptocurrency-part-2-tax-loss-harvesting-and-wash-sales), [my own blog](https://phil.mk/us-tax-law-and-cryptocurrency-part-2-tax-loss-harvesting-and-wash-sales/), [Medium](https://medium.com/phil-mk/us-tax-law-and-cryptocurrency-part-2-tax-loss-harvesting-and-wash-sales-92719b6a4b33), [Reddit](https://www.reddit.com/r/CryptoCurrency/comments/lsg7h6/us_tax_law_and_cryptocurrency_part_2_tax_loss/), and [Publish0x](https://www.publish0x.com/phil-mk/us-tax-law-and-cryptocurrency-part-2-tax-loss-harvesting-and-xzwzrmo).