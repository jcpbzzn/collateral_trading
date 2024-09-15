# Collateral Trading

## Introduction

### Repurchase Agreement

Repo is essentially a secured loand and the name stands for *sale and repurchase agreement* [(Choudhry, 2002)](#choudhry-2002).
In a classic repo one party will enter into a contract to sell securities, simultaneously agreeing to purchasing them back at a specified future date and price. The securities can be bonds or equities but also money market instruments such as T-Bills. The buyer of the securities is handing over cash, which on the termination of the trade will be returned to them, and on which they will receive interest.

The seller in a classic repo is selling or *offering* stock, and therefore receiving cash, whereas the buyer is buying or *bidding* for stock, and consequently paying cash. So if the one week repo interest rate is quoted by a market-making desk at as "5½ - 5¼", this means that the market-maker will bid for stock, that is, lend the cash, at 5.50% and offers stock or pays interest on borrowed cash at 5.25%. In some markets the quote is reversed. In a repo transaction, the seller enters into a *repo* while the buyer enters into a *reverse repo*.

The two main types of repo transactions are *term repo* and *open repo*. In a *term repo*, the lenght of the repurchase agreement is set upfront, while in an *open repo* the transaction is rolled everyday. The advantage of an term repo is the ability to lock in the funding cost (repo rate) for a specific lenght of time; on the other hand, unwinding the transaction prior to term date is likely to generate some early termination charges. An open repo, is rolled everyday and each of the party has the legal entitlement to terminate the transaction at any point for T+1. 

At the *start date* the loan amount, i.e. the cash amount which is delivered in exchange of the collateral is computed as follows.

$$
\text{Loan Amount} = \text{Dirty Price} \cdot \text{Notional} \cdot \text{Haircut}
$$

Where the *haircut* represents the difference between the collateral value and the cash lent out in the repo, and is a measure to reduce risk from the perspective of buyer. The *haircut* or *initial margin* protects the buyer against:
- a sudden fall in the market value of the collateral;
- illiquidity of collateral;
- other sources oif volatility of value (for example, approaching maturity);
- counterparty risk.

At the *termination date*, the amount that the *seller* of the collateral has to pay back to the *buyer* of the collateral is:

$$
\text{Termination Amount} = \text{Loan Amount} \cdot \text{Repo Rate} \cdot \frac{\text{n days}}{\text{days in year}}
$$

Repo transactions from a buy-side point of view, are used for several purposes:
- raise leverage (use holdings as collateral to get a loan to buy more holdings)
- short securities (borrow the security to deliver to the counterparty to which they shorted)
- yield enchancement (get an extra return from lending the 

## References

<a id="choudhry-2002"></a>Choudhry, M. (2002). *The repo handbook*. Butterworth-Heinemann.
