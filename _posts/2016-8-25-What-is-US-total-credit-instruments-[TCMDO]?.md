---
layout: post
title: What is US total credit instruments [TCMDO]?
---

**_v1.0_**

The short answer is that the number represents all of the [credit](http://hackeconomics.com/what-is-credit/) issued to consumers, corporations, and the government. There is a way to look at the specifics which I'm going to do below, however, this has a "Through the looking glass" feel to its complexity. So here goes. The FRED series _Total Credit Market Debt Owed_ has a series number of FL894104005. The series which make up the sum of this series can be found [here](https://www.federalreserve.gov/apps/fof/SeriesAnalyzer.aspx?s=FL894104005&t=). To compute it we need to add up:

```
= + FL144104005 + FL154104005 + FL214104005 + FL314104005 + FL413065005 + FL264104005 + FL404104005 + FL614104005 + FL704104005 + FL674122005 + FL644104005 + FL543169373 + FL664104005 + FL734104005 + FL504104005 + FL513169333
```

The description of each series:

```
+ FL144104005.Q	Nonfinancial business; debt securities and loans; liability
+ FL154104005.Q	Households and nonprofit organizations; debt securities and loans; liability
+ FL214104005.Q	State and local governments, excluding employee retirement funds; debt securities and loans; liability
+ FL314104005.Q	Federal government; debt securities and loans; liability
+ FL413065005.Q	Agency-and GSE-backed mortgage pools; total mortgages; asset
+ FL264104005.Q	Rest of the world; debt securities and loans; liability
+ FL404104005.Q	Government-sponsored enterprises; debt securities and loans; liability
+ FL614104005.Q	Finance companies; debt securities and loans; liability
+ FL704104005.Q	Private depository institutions; debt securities and loans; liability
+ FL674122005.Q	Issuers of asset-backed securities; debt securities; liability
+ FL644104005.Q	Real estate investment trusts; debt securities and loans; liability
+ FL543169373.Q	Life insurance companies, general accounts; FHLB advances; liability
+ FL664104005.Q	Security brokers and dealers; debt securities and loans; liability
+ FL734104005.Q	Holding companies; debt securities and loans; liability
+ FL504104005.Q	Funding corporations; debt securities and loans; liability
+ FL513169333.Q	Property-casualty insurance companies; FHLB advances; liability
```

Each of these series is made up of other series which you can peruse at your leisure [here](https://www.federalreserve.gov/apps/fof/SeriesAnalyzer.aspx?s=FL894104005&t=).
