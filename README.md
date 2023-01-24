# Temporal-Analysis
Repository to host all temporal analysis data visualization projects

## Iphone Sales Dataset
Goal: Analyze the sales pattern of iPhone over time.
Excel file iPhoneSales.xlsx contains iPhone unit sales by quarter from Q3 2007 to Q4 2018 (Data Source: Statista).

**Background:** 
The Apple iPhone was first sold in June 2007. Apple stopped reporting unit sales figures from first quarter 2019.

Note that the quarterly periods for Apple's fiscal year include the following:
early October to late December of the previous year (first quarter)
early January to late March of the stated year (second quarter)
early April to late June of the stated year (third quarter)
early July to late September of the stated year (fourth quarter)

**Data Fields:** 
1. Date
    Q1: 01/01
    Q2: 04/01
    Q3: 07/01
    Q4: 10/01
2. Sales (in million units)

---
## E-Bay Auction Sniping Analysis

**Background:** 
In online auctions with fixed ending times, auction sniping refers to the behavior of placing a bid likely to exceed the current highest bid (which may be hidden) as late as possible (sometimes seconds before the end of the auction) giving other bidders no time to outbid the sniper.

**Data Fields:** 
auctionid: unique identifier of an auction
bid: the proxy bid placed by a bidder
bidtime: the time in days that the bid was placed, from the start of the auction
bidder: eBay username of the bidder
bidderrate: eBay feedback rating of the bidder
openbid: the opening bid set by the seller
price: the closing price that the item sold for (equivalent to the second highest bid + an increment)
item: auction item (Cartier wristwatch, Xbox game console)
auction_type: 3 day auction, 5 day auction, 7 day auction



