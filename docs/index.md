# FAQ

#### **What is Hit/Miss?**

- Hit: A transaction that ended in profit. 
- Miss: A transaction that ended in loss.

For Multiple Legs Transaction:

- A transaction will be counted as hit, if the entry/exit of all the legs results in an overall profit.
- A transaction will be counted as miss, if the entry/exit of all the legs in an overall loss.

<figure markdown> <!--  -->
  ![Hit Miss](img/hit|miss.png){ width="auto" }
  <figcaption>Hit Miss</figcaption>
</figure>

**Note:** In case of trade type, we show each leg as hit/miss if the leg's entry/exit resulted in a profit/loss.


#### **How Strike Index Works?**

ATM/ITM/OTM:

ITM 2 CE and OTM 2 PE will be the same strike prices. For CE/PE the ITM/OTM will be the reverse.

If current future price is 10,000.

| CE  | Strike Price  | PE  |
|--------|--------|-------|
| OTM 2  | 10,200 | ITM 2 |
| OTM 1  | 10,100 | ITM 1 |
| ATM    | 10,000 | ATM   |
| ITM 1  | 9,900  | OTM 1 |
| ITM 2  | 9,800  | OTM 2 |


<figure markdown> <!--  -->
  ![Strike Index](img/strikeIndex.png){ width="auto" }
  <figcaption>Strike Index</figcaption>
</figure>


Explanation from [investopedia](https://www.investopedia.com/ask/answers/042715/what-difference-between-money-and-out-money.asp)


- A call option with a strike price of $132.50, for example, would be considered ITM if the underlying stock is valued at $135 per share because the strike price has already been exceeded. 
- A call option with a strike price above $135 would be considered OTM because the stock has not yet reached this level.

- A put option with a strike price of $75 is considered in the money if the underlying stock is valued at $72 because the stock price has already moved below the strike. 
- That same put option would be out of the money if the underlying stock is trading at $80.

We will try to improve the user interface so that it is not confusing in the future.

Thank you for your interest and support for the platform.